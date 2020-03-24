# Episode 007:  BookKeeper Continued

- Hosted by @sijie
- Recorded on 03/22/2020

![](/image/007.png)

## Table of Content

- 00:00:00 - Welcome to TGIP-CN!
- 00:00:00 - Week in review

## Week in Review

- TGIP-CN: https://github.com/streamnative/tgip-cn
- [2020 Pulsar User Survey Report](http://pulsar.apache.org/blog/2020/03/17/announcing-the-apache-pulsar-2020-user-survey-report/)
- Kafka-on-Pulsar Webinar on 10 AM PST, March 31,Co-hosted by StreamNative and OVHcloud.
    Registration Link: https://zoom.us/webinar/register/6515842602644/WN_l_i-3ekDSg6PwPFn7tqRvA

## Show Notes

* BookKeeper continued
    * Fencing Mechanism
    * AutoRecovery
* BookKeeper on Kubernetes
    * Cookie & Bookie Identifier
        * Bookie Identifier
            * iPhone
            * Hostname
            * Advertised Address
            * Multiple Listeners (*)
        * DaemonSet vs StatefulSet
    * Persistent Volume vs Local Persistent Volume
    * AutoRecovery
        * running as part of bookies: `using bin/bookkeeper shell`
        * running outside of bookies: `kubectl scale`

## Reference 

- Local Persistent Volume (Kubernetes 1.14+): https://kubernetes.io/blog/2019/04/04/kubernetes-1.14-local-persistent-volumes-ga/
- StatefulSet: https://kubernetes.io/docs/concepts/workloads/controllers/statefulset/
- DaemonSet: https://kubernetes.io/docs/concepts/workloads/controllers/daemonset/
- Study note: https://hackmd.io/RX9OSGJxT5yYn2GLIvYH8A
- Recorded video: https://www.bilibili.com/video/BV1T741147B6?p=6
- Tech blog: 
