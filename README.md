# knative-image
knative image Dockerfile (used by docker hub)


| gcr image | docker-hub image |
|:-|:-|
|gcr.io/knative-releases/github.com/knative/serving/cmd/queue@sha256:e19ca17d2b729904d2662a30b6c5c27cf4b62fd64baef2da4125525a4f9346e5|ljchen/knative_serving_cmd_queue:0.4.0 |
|gcr.io/knative-releases/github.com/knative/serving/cmd/queue@sha256:e19ca17d2b729904d2662a30b6c5c27cf4b62fd64baef2da4125525a4f9346e5 | ljchen/knative_serving_cmd_activator:0.4.0 |
|gcr.io/knative-releases/github.com/knative/serving/cmd/autoscaler@sha256:22068b4f2d34ae9b65a455413b9f7f62d29c61b4b977ea0983f69dfff4db4d8d
 | ljchen/knative_serving_cmd_autoscaler:0.4.0 |
|gcr.io/knative-releases/github.com/knative/serving/cmd/controller@sha256:c9987a7b21400bd3afa01eeed54f390a7d1d24b25d87219803cdfb294a969379
 | ljchen/knative_serving_cmd_controller:0.4.0|
|gcr.io/knative-releases/github.com/knative/serving/cmd/webhook@sha256:b5b103242842f726d0292b3fb6add876ef97983852c176a81d42bbbe3d6ac932
 |ljchen/knative_serving_cmd_webhook:0.4.0 |

|gcr.io/knative-releases/github.com/knative/eventing-sources/cmd/manager@sha256:1c7a802f2b392581a02536fa00ad581b1f47be4a9cebab48f9bdc8e3cd5dffe0
 | ljchen/knative_eventing-sources_cmd_manager:0.4.0|
| gcr.io/knative-releases/github.com/knative/eventing/cmd/controller@sha256:037f13e1567a145d58c49651c6cabca4dac765c1e2e62faab0a488561b5ef9ec
| ljchen/knative_eventing_cmd_controller:0.4.0|
|gcr.io/knative-releases/github.com/knative/eventing/cmd/webhook@sha256:f2b3caef895721036415027fdc7c44ebad5dfa5f29b3cb5b645ea4bf45a71d58
 | ljchen/knative_eventing_cmd_webhook:0.4.0|
|gcr.io/knative-releases/github.com/knative/eventing/pkg/provisioners/inmemory/controller@sha256:3ef04add5f8286af6571161663129583ece32b7c457fbb2115e9e4c12001f980
 |ljchen/knative_eventing_pkg_provisioners_inmemory_controller:0.4.0 |
| gcr.io/knative-releases/github.com/knative/eventing/cmd/fanoutsidecar@sha256:e14cd81992483466efdf299924739c64256ab7705e8f8622063137566dd5772d
|ljchen/knative_eventing_cmd_fanoutsidecar:0.4.0 |


|gcr.io/knative-releases/github.com/knative/build/cmd/creds-init@sha256:9243ee302895cc3925b5c6670886b0051d18b97c356723287ba2292bf62641e3
 | ljchen/knative_build_cmd_creds-init:0.4.0|
| gcr.io/knative-releases/github.com/knative/build/cmd/git-init@sha256:bef1d2d1fbaa80a130fb322dbfe3895ae17ce8e74921762e5b16a24157896105
| ljchen/knative_build_cmd_git-init:0.4.0|
| gcr.io/knative-releases/github.com/knative/build/cmd/nop@sha256:a0481df4fde8afe761c7a614c63b65069ef7c4c7b7715a29b03170eed8029c02
| ljchen/knative_build_cmd_nop:0.4.0|
| gcr.io/knative-releases/github.com/knative/build/cmd/controller@sha256:c48663d589ac034d091dd95e746b6a2733950911e9959a012c5773e5b6a77ee3
| |
|gcr.io/knative-releases/github.com/knative/build/cmd/webhook@sha256:bcbc9fd994b84d9fe84400e04e52628ccc2b12b001d6c35a263ed363e55d6a6b
 | ljchen/knative_build_cmd_controller:0.4.0|
|gcr.io/cloud-builders/gcs-fetcher
 | ljchen/knative_build_cmd_webhook:0.4.0|
