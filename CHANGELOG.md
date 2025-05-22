## 0.1.0 (2025-05-22)


### Features
* Launch Host Configuration feature (#636) ([`dd2071d`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/dd2071d1d01d6cd811531bc1d689c114a7e760e5))
* **experimental**: add support for chunkInt parameter type ([`4c517b4`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/4c517b4a37c35ee4cc8c1ba79bfc6bc1cb29f250))
* **HOST_CONFIGURATION_FEATURE**: Prevent Windows ACL inheritance for host config script and log and grant full control to Administrators ([`98dfbfc`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/98dfbfc9dbebdb02145c8413a76fe82f45635c58))
* **HOST_CONFIGURATION_FEATURE**: delimit host configuration script with banners in worker logs and shutdown host on failure ([`f08bca8`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/f08bca8656488d9af992b1dca4b4969f5bdf96b6))
* Support running configuration scripts after worker reaches STARTED state (#601) ([`d925c65`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/d925c65a052579675443d004295c2b70f019fe9b))
* configurable session root directory (#513) ([`dd541a1`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/dd541a12eac344e109ca283166f978a20af8439c))
* run job attachment output upload as job user (#495) ([`678f29a`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/678f29a6ae86265b6a0f912cdcc52a2ceccb7b62))
* directly send cancel OS signals on Linux (#479) ([`a0fc35c`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/a0fc35c419bba964ffa5146f8bb65c54064fc929))
* integrate with job attachment download cli as a openjd action run (#476) ([`07abc76`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/07abc76dc9bdd46a7281a6349b1bb7eaaa808810))
* include specific session runtime logs in the worker log (#422) ([`be55928`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/be55928bb55ca361a2900b16f599ccc1f1b03b7c))
* add job user override for windows (#372) ([`84c83bd`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/84c83bdffbce7b44f46668cce3ec36ac596fab5d))
* add success or fail metric on Job Attachment calls (#352) ([`ac1e5e0`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/ac1e5e0d4b7ba8c85ec868c84ee5cabf4980f091))
* add deadline client lib, OpenJD Sessions to boto3 header (#351) ([`51fc0f1`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/51fc0f10b02fde81904b4688e20c91adb83c3c8e))
* differentiate step actions from non-step actions in logs (#292) ([`a6d55e3`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/a6d55e3849cd4c374e91d184ed3ad40bd88d491f))
* public release (#271) ([`ed1e14d`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/ed1e14df818e8161490a5c6b884320eeb7b6832e))
* remove deprecated features (#277) ([`d984094`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/d984094f74b9ad60dd0bc82ec3eb917cda4e138d))
* adds data on action kind and queue length to logs (#266) ([`bb10c47`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/bb10c4758dab094738b23859a3e8aae64fac4850))
* overhaul agent logging to introduce structured logs (#216) ([`abed8c9`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/abed8c95c932f0890eb03f5ed383ce8def3a37dc))
* **installer**: allow ec2 instance profile by default (#259) ([`7e4d947`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/7e4d9474bd96d1d0b7a7ba749acca80d1266b0a3))
* aws config directory managed by agent (#254) ([`2f4fd8a`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/2f4fd8a7a2431f8b4bbbfd92cbc435095be8278b))
* **installer**: detect default AWS region on EC2 (#250) ([`3db8685`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/3db86851bc9bcc9afec33c9fdd1b981897266b12))
* cleanup asset_sync session with os_user (#251) ([`b68922e`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/b68922e37d95c37b3eec88b990d88b7fba60875e))
* **windows-installer**: configure AWS region in Windows service (#242) ([`adf164f`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/adf164ff56b56bc48837012d99bc086b1120193a))
* agent logs contain more verbose API request/response information (#215) ([`6e8e566`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/6e8e566dadfd39c77737ac5243276256f87d492c))
* session cleanup on windows (#212) ([`93f4305`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/93f43053ccd498fd913b31b8aa96c4d43fae7157))
* **windows-installer**: grant and validate agent user permissions (#206) ([`0d8e3de`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/0d8e3de5ee4ccdadffbbc365c2e822ff62efc0fd))
* Add telemetry event for uncaught exceptions (#203) ([`9a17a07`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/9a17a0786fe47b1e0ad0d69ee55c0746823a95a5))
* retool scale-in behaviour (#193) ([`40390e9`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/40390e92d3e799f5299233b6d030a9e66582e18c))
* windows service (#207) ([`1d97970`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1d979709941e2c2b116cb7932d664a64584a95d4))
* **windows-installer**: add client telemetry opt out option (#210) ([`7551869`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/7551869124f8a7ef219888b52e472f632ec68b0d))
* windows support (#205) ([`80e8ec4`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/80e8ec423ced2130792d95af7690bb9b64b77565))
* change OpenJD's session directory path, and add `--retain-session-dir` command option (#196) ([`091608c`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/091608c65b50e6fecac94dfff4e2f088c1f49926))
* Add job and session metadata to the environment of a job (#189) ([`92b6d17`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/92b6d17e91cfd19981f0e19d66c47e614150eb44))
* Cancel Job Attachments session action when transfer rates drop below threshold (#143) ([`c49bbb4`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/c49bbb498949e3ed2b469714717018669134d5c2))
* report action timeout as failed with timeout message (#165) ([`ff36123`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/ff3612387f9b010359480367bea62f67235be3aa))
* provision ownership on /var/lib/deadline/credentials directory (#145) ([`3b3e7af`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/3b3e7af471ab4f7947163f8978d2d9de0baad091))
* adds compatibility with upcoming BatchGetJobEntity API change (#139) ([`5197e57`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/5197e5767a5134e192602ecc85d5d98f0f32f24e))
* include Queue ID in sync_inputs, sync_outputs telemetry (#135) ([`c3579af`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/c3579af41735715e74acfec56b8be87a6995ecac))
* compatibility with BatchGetJobEntity API changes for jobRunAsUser (#133) ([`08d7ba6`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/08d7ba6ebd219e202f545885937d0ed02aee9811))
* rename "updateTime" to "updatedAt" in UpdateWorkerSchedule API request (#131) ([`f607954`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/f607954112b7f1298b95afc3b1dc16322ce6bfbe))
* emit job attachment transfer statistics as telemetry events (#104) ([`ccaa097`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/ccaa09759ed9533e5388fa4ecef60fa17cbe098d))
* rename impersonation options to use run-as nomenclature (#92) ([`5165a4d`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/5165a4d2ade202b4a85a78473f6d9d160bba1f06))
* print versions of 1st party dependencies to worker log (#82) ([`b98be06`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/b98be067266dfdf1f1f52bc3ab3de6eefdd040f8))
* **install**: Adding vfs install path to install parameters (#58) ([`60959c0`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/60959c098eda9bce46f83123b6b0957f6504432e))
* add host metrics logging (#45) ([`1718c57`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1718c575ae73deb5f6a324da78bf7c5f24ab75d8))
* session lifecycle log improvements (#51) ([`f658fff`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/f658fff5c90df32fc0b9d650072b9e32eaf2990c))
* log completed session actions (#49) ([`bb4e3bd`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/bb4e3bd37d69fc09dd75bca54108ccf4232a7013))
* Adds telemetry client calls to worker (#42) ([`1e96738`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1e967381832d45fc173a25dcd8efd0278b206024))
* update to the new job schema ([`9aafbbe`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/9aafbbe57c1c07b19f5db1a6de2d8d135ef0a2ea))
* add --no-install-service to installer and add integration test (#13) ([`4237090`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/4237090ef6ec52e394ad6609f29c99dc6ac3fd94))
* Support Storage Profiles path mapping rules when syncing inputs/outputs (#10) ([`c6e549d`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/c6e549d2ac05b648365a74d188efd3647c89bbca))

### Bug Fixes
* update worker workflows ([`4b2ce81`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/4b2ce819042654022c763a2d4c88f97a4d543d44))
* Cleanup log file before starting host config if the file already exists (#634) ([`6466c4f`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/6466c4fbd509867f877a17af1a4a95693590808b))
* **ASSET_SYNC_JOB_USER_FEATURE**: NonValidInputError failures and uploading files from input job attachment directories (#612) ([`4c12664`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/4c126648a657df83e065c77274c965b8d0ad283e))
* Worker Agent Crashes on corrupted cached credentials (#614) ([`7f1ec05`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/7f1ec05d86035febd68daffa603d8da404b8854a))
* High memory use when running job attachment test cases (#576) ([`b88b8e1`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/b88b8e184ae3b677aac2882afca25accfe27f925))
* unexpected GPU memory configurations crash worker agent (#574) ([`b423bfb`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/b423bfb68e258c2b86e90925669572691ccab2c3))
* worker agent unable to start without EC2 metadata access (#572) ([`5e73148`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/5e7314839a3cd9da7bfa50ab9f4198fcabb5edf4))
* install-deadline-worker on Windows creates session root directory without read and traversal permissions for Users (#563) ([`29e7aee`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/29e7aee77ab362094b219dd5ec20920a1b859078))
* **experimental**: task with step-step dependency upload job inputs as outputs (#529) ([`abe0fb0`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/abe0fb0f2c4b04de1490943502f83061e160d938))
* more robust config file modifications in install-deadline-worker (#512) ([`1060b4b`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1060b4bd29890c0b76ece8665b0415cb5a3303e2))
* worker state file saved on AMI causes multiple instances sharing same worker ID (#527) ([`ec001c9`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/ec001c9830b0fd7639248a2b2bc892787993c5b2))
* skip attachment upload when outputs not modified (#524) ([`972df4e`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/972df4ead8311967ad26844f0445859cae9ae483))
* update log kind to differentiate sync input and sync output (#523) ([`af28588`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/af285880ae66c697534aabae2f28fbc626873fa8))
* increase e2e test instance size (#468) ([`2f7cc57`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/2f7cc57169d710f3da21412ae0f40f5b1e171f05))
* non-user-friendly error when trying to install the worker agent as domain user (#457) ([`15afe89`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/15afe89930f99f92346a4b96806c4c68d76bdbae))
* increase default instance size (#441) ([`e8f0117`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/e8f01178076979210a0a64d079468d142224481b))
* crash when host has multiple NVIDIA GPUs (#435) ([`760118c`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/760118c0ab8157ecc5087fc919f6773b0cd6c376))
* prevent test s3 buckets not being able to be created in some regions (#426) ([`7dfd09b`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/7dfd09b8991cf51adf5c16f54d2ab2ff60e3a965))
* Add job cancellation when test is finish to avoid side effect (#425) ([`2b521a5`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/2b521a5d37726666463e5213f604775c2ea3d058))
* vague error message when no AWS region specified (#413) ([`0d5ccad`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/0d5ccadebab5aca5b562abf6d8032aa79ca51678))
* WindowsPath is not JSON serializable during session cleanup (#412) ([`5d5055c`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/5d5055cf728a98769415a30a923eea057b8d9683))
* Ensure scheduler drain and status update on Windows service shutdown (#408) ([`f269b67`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/f269b67d415e0203a49b9f85bf8b811b345f96e6))
* allow retries to tests (#397) ([`87613eb`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/87613ebf9f1cf6342f43f012378f28ad50357e45))
* Agent Logs to /var/log/messages when running as a service on Linux (#396) ([`b2368ed`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/b2368edeaec80b6c31132195dbdf4579b5e7e225))
* --run-jobs-as-agent-user crashes on windows (#395) ([`6fef296`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/6fef2969ef5cd4eb12adc76eded4587f447c0726))
* install-deadline-worker doesn't create queues persistence dir on Windows (#377) ([`bd40074`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/bd40074f3117d78e2080b01bb439cc1f146091eb))
* posix installer succeeds if agent-user does not already exist (#378) ([`17435b1`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/17435b15941305baf09ac772eeb6723a66ec7902))
* jobRunAsUser always removed in BatchGetJobEntity JobDetails (#349) ([`b6a64de`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/b6a64ded6b725822d097ac9fad8f12c4e63e9388))
* fail on BatchGetJobEntity jobRunAsUser validation with a job user override  (#346) ([`c0dd3b3`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/c0dd3b35db2faef3296277cbf66e3dc42adeb80f))
* install-deadline-worker on Linux assumes agent os group matches username (#345) ([`4ed1136`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/4ed1136e1ed6e5d7cdfcbd9cb5d0848ff4bd316e))
* error due to out-of-range process exit code (#339) ([`7d4ec30`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/7d4ec30f15af952cdcf03d3c28d9ce9608d861ab))
* handle case where BatchGetJobEntity returns no jobRunAsUser (#293) ([`616e16c`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/616e16c293ae544fe948528b485a6892c36bf0a6))
* provide region in queue AWS configuration (#289) ([`efeecfe`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/efeecfe354cdfe321fe96718ed51704e67ab847a))
* stop the running Windows service before re-installation. (#288) ([`0587b60`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/0587b6026622424584e46717561d6ee61879bbba))
* example config file inaccurately documents allow_ec2_instance_profile (#278) ([`1d1ecc1`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1d1ecc165384c6f14ace4465236460ba12b176ee))
* set log file encoding to utf-8 (#267) ([`1008083`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/10080837558bc369c35243b5c15af82d45e35467))
* unhandled exception unloading user profile (#264) ([`62a404b`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/62a404b0d9db8d95e02b4e977d4a343f2444cc00))
* remove time field from structured logs (#263) ([`d246abf`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/d246abf1595d07e5cb99bb9a451d3fb7162baf2f))
* handle OSError when detecting GPU capabilities (#255) ([`677fda6`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/677fda63e51a8c436c47faf9650b147a462b2a31))
* handle IMDS disruptions gracefully (#249) ([`ea6b701`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/ea6b70102add121362da7009724146c604ebfa45))
* return sessionactions if Session is stopped (#252) ([`1230d89`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1230d89152ae72bae77747da32e551dbc92c9c98))
* insufficient Windows ACLs for job user AWS config files (#246) ([`f5e2f52`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/f5e2f52aa747976f15540a6f0da561a0f7faa57d))
* NEVER_ATTEMPTED session actions should not report startedAt or endedAt (#237) ([`99fd7d3`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/99fd7d385dedc25c22aeaecee7247bef3e682fa0))
* improve logging when getting secret (#184) ([`d3e2e0c`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/d3e2e0c863efd2af8b1eeb0a6f3173b7c6b6a23d))
* increasing default password length for windows users (#236) ([`c411c85`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/c411c851395fa6a46a174d9709b3b907dd9796f1))
* change windows logon type from NETWORK to INTERACTIVE (#234) ([`82a5c11`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/82a5c11195102e3334961b4420915feccfc849b0))
* Fail jobs configured to run as worker agent when Admin (#230) ([`7ce01a8`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/7ce01a8731005178a6da964c24870b3fc9d57f03))
* change OpenJD's session root directory to /sessions (#222) ([`3b68342`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/3b68342bc12307e63f84214b310ed616437c1c8e))
* improve error messaging for Windows logon (#219) ([`de23226`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/de232262d503da01f5f1aa974d985555fe51008a))
* **install.sh**: update ownership and permissions for session root directory (#201) ([`230b73c`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/230b73c5c6c472256db68ab43ddd83203889d245))
* complete all actions following unsuccessful actions as NEVER_ATTEMPTED (#190) ([`d266c0f`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/d266c0f9740bd82d4ca85b7de2031e68edfd8b77))
* handle non-existent queue jobRunAsUser on worker host (#176) ([`1049a48`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1049a48f0ff045160f5524eb25c3f97a42114fcb))
* Set shutdown_on_stop value in config file. (#164) ([`858f621`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/858f621e4939b0b5bc32262bc90cc4fa80dd148e))
* Terminating all VFS processes when cleaning up session (#149) ([`50178ed`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/50178ede860949b766f85ef7f3e0c586ce8bc8e9))
* permissions on /var/log/amazon directory (#162) ([`1acfffc`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1acfffc69040061b3e9fa02894e2a7a7cbab204d))
* no longer sigterm agent when running jobs as same user (#161) ([`fe12ad3`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/fe12ad32076a3ce2a87ae84f1dbe46a4fc8c0121))
* don't invert shutdown_on_stop config file setting's meaning (#155) ([`1a7329f`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1a7329f039ad9c164c0ee2c5c05e333462fdf892))
* crash if queue has no user defined (#127) ([`3b62715`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/3b6271590517820e2d187a853fbfa023cf306a09))
* job attachment output upload blocking UpdateWorkerSchedule API requests (#122) ([`f2b3893`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/f2b38939b2b5936979bdbd8d562fd5454de3dfb6))
* OpenJD architecture capability reporting on ARM (#118) ([`73a2877`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/73a287792381542f68138d137086bf7afd8747c0))
* use release environment in release workflow integ tests (#112) ([`3ae3a16`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/3ae3a169ddb3e738bf424597c2156d15714118cb))
* "jobs_run..." -> "run_jobs..." (#93) ([`1cc9f34`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1cc9f3412fc3c2118133560e03705f330d68e168))
* Adding os_user to FileSystemPermissionSettings for use in the deadline vfs (#94) ([`1625ce5`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1625ce51f2691a335bc3a1cd4c06a9a793876698))
* avoid truncating sessionaction logs (#86) ([`47dca3e`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/47dca3e35d332401c4ff365336736717666d0532))
* mock HostMetricsLogger in entrypoint tests (#70) ([`b9df0a9`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/b9df0a91e8bca4c75ac3571e9b4248800d759158))
* use NEVER_ATTEMPTED after session action failures (#74) ([`5060e16`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/5060e16447a35fa8cf543e54f07b43223e710b7e))
* handle CONCURRENT_MODIFICATION conflict from UpdateWorkerSchedule (#69) ([`da4da41`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/da4da414c6268d8081526dcfb542ca4aa4fc30af))
* mock host metrics logger in worker module for tests (#64) ([`0628cd2`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/0628cd2be49031268c94529ad88a05e85e2dc193))
* set RunStepTaskAction end time to asset sync completion time (#11) ([`2fd6c47`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/2fd6c47b18175e44c8593aa31899e67109ebe343))
* respect service's suggested retryAfter when throttled (#39) ([`d83066a`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/d83066adaa7f17990ece7f8e90a026b113bbc1ae))
* add job_run_as_user to integ test (#57) ([`962808f`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/962808fb850df31fcd7827a605d5e331045bc938))
* **job_attachment**: Change osType to rootPathFormat (#37) ([`5a39c25`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/5a39c251919a3bc72f2a1dfb9830f4a5e4a9fc50))
* remove the recursive ownership/permissions changes (#26) ([`1c3a9b5`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1c3a9b54460a33e973305f8d48dfacbf2c237e7e))
* remove old schema workaround (#32) ([`c37bb47`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/c37bb47b818094a90c00c38ffe5b7940fcc6fab3))
* Use status instead of targetStatus in UpdateWorker. (#29) ([`a22e7df`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/a22e7df0dd30e0b9fd4a2ac3f8f495523fd656fb))
* duplicate layers of API request retries and integer overflow in backoff ([`4905915`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/4905915a1d604ae03091d223a638b6c4a9ae0033))
* Fixing name mismatch in testing scripts (#19) ([`20c3b72`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/20c3b72894214d0b08a0188f3cf4f0500b3ffd23))
* use the proper entity key variable (#15) ([`8f6f9b4`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/8f6f9b4ada3f94ff57658908c8ec3310a7297f8c))
* use try/except/finally clause in SyncInputJobAttachmentsAction, to ensure that the update action happens (#12) ([`0d64cbd`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/0d64cbd6a567029e99537369728b3f1aa62b1882))
* Update worker binary to deadline-worker-agent where necessary (#7) ([`044f0fa`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/044f0fa5ce28e9764589373f09c2e07195492764))
* fail installer when worker agent path is not found (#4) ([`f397f80`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/f397f801c2e63e8e8f55432057aa2f71a8f70aed))

## 0.1.0 (2025-05-22)


### Features
* Launch Host Configuration feature (#636) ([`dd2071d`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/dd2071d1d01d6cd811531bc1d689c114a7e760e5))
* **experimental**: add support for chunkInt parameter type ([`4c517b4`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/4c517b4a37c35ee4cc8c1ba79bfc6bc1cb29f250))
* **HOST_CONFIGURATION_FEATURE**: Prevent Windows ACL inheritance for host config script and log and grant full control to Administrators ([`98dfbfc`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/98dfbfc9dbebdb02145c8413a76fe82f45635c58))
* **HOST_CONFIGURATION_FEATURE**: delimit host configuration script with banners in worker logs and shutdown host on failure ([`f08bca8`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/f08bca8656488d9af992b1dca4b4969f5bdf96b6))
* Support running configuration scripts after worker reaches STARTED state (#601) ([`d925c65`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/d925c65a052579675443d004295c2b70f019fe9b))
* configurable session root directory (#513) ([`dd541a1`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/dd541a12eac344e109ca283166f978a20af8439c))
* run job attachment output upload as job user (#495) ([`678f29a`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/678f29a6ae86265b6a0f912cdcc52a2ceccb7b62))
* directly send cancel OS signals on Linux (#479) ([`a0fc35c`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/a0fc35c419bba964ffa5146f8bb65c54064fc929))
* integrate with job attachment download cli as a openjd action run (#476) ([`07abc76`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/07abc76dc9bdd46a7281a6349b1bb7eaaa808810))
* include specific session runtime logs in the worker log (#422) ([`be55928`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/be55928bb55ca361a2900b16f599ccc1f1b03b7c))
* add job user override for windows (#372) ([`84c83bd`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/84c83bdffbce7b44f46668cce3ec36ac596fab5d))
* add success or fail metric on Job Attachment calls (#352) ([`ac1e5e0`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/ac1e5e0d4b7ba8c85ec868c84ee5cabf4980f091))
* add deadline client lib, OpenJD Sessions to boto3 header (#351) ([`51fc0f1`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/51fc0f10b02fde81904b4688e20c91adb83c3c8e))
* differentiate step actions from non-step actions in logs (#292) ([`a6d55e3`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/a6d55e3849cd4c374e91d184ed3ad40bd88d491f))
* public release (#271) ([`ed1e14d`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/ed1e14df818e8161490a5c6b884320eeb7b6832e))
* remove deprecated features (#277) ([`d984094`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/d984094f74b9ad60dd0bc82ec3eb917cda4e138d))
* adds data on action kind and queue length to logs (#266) ([`bb10c47`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/bb10c4758dab094738b23859a3e8aae64fac4850))
* overhaul agent logging to introduce structured logs (#216) ([`abed8c9`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/abed8c95c932f0890eb03f5ed383ce8def3a37dc))
* **installer**: allow ec2 instance profile by default (#259) ([`7e4d947`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/7e4d9474bd96d1d0b7a7ba749acca80d1266b0a3))
* aws config directory managed by agent (#254) ([`2f4fd8a`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/2f4fd8a7a2431f8b4bbbfd92cbc435095be8278b))
* **installer**: detect default AWS region on EC2 (#250) ([`3db8685`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/3db86851bc9bcc9afec33c9fdd1b981897266b12))
* cleanup asset_sync session with os_user (#251) ([`b68922e`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/b68922e37d95c37b3eec88b990d88b7fba60875e))
* **windows-installer**: configure AWS region in Windows service (#242) ([`adf164f`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/adf164ff56b56bc48837012d99bc086b1120193a))
* agent logs contain more verbose API request/response information (#215) ([`6e8e566`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/6e8e566dadfd39c77737ac5243276256f87d492c))
* session cleanup on windows (#212) ([`93f4305`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/93f43053ccd498fd913b31b8aa96c4d43fae7157))
* **windows-installer**: grant and validate agent user permissions (#206) ([`0d8e3de`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/0d8e3de5ee4ccdadffbbc365c2e822ff62efc0fd))
* Add telemetry event for uncaught exceptions (#203) ([`9a17a07`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/9a17a0786fe47b1e0ad0d69ee55c0746823a95a5))
* retool scale-in behaviour (#193) ([`40390e9`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/40390e92d3e799f5299233b6d030a9e66582e18c))
* windows service (#207) ([`1d97970`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1d979709941e2c2b116cb7932d664a64584a95d4))
* **windows-installer**: add client telemetry opt out option (#210) ([`7551869`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/7551869124f8a7ef219888b52e472f632ec68b0d))
* windows support (#205) ([`80e8ec4`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/80e8ec423ced2130792d95af7690bb9b64b77565))
* change OpenJD's session directory path, and add `--retain-session-dir` command option (#196) ([`091608c`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/091608c65b50e6fecac94dfff4e2f088c1f49926))
* Add job and session metadata to the environment of a job (#189) ([`92b6d17`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/92b6d17e91cfd19981f0e19d66c47e614150eb44))
* Cancel Job Attachments session action when transfer rates drop below threshold (#143) ([`c49bbb4`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/c49bbb498949e3ed2b469714717018669134d5c2))
* report action timeout as failed with timeout message (#165) ([`ff36123`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/ff3612387f9b010359480367bea62f67235be3aa))
* provision ownership on /var/lib/deadline/credentials directory (#145) ([`3b3e7af`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/3b3e7af471ab4f7947163f8978d2d9de0baad091))
* adds compatibility with upcoming BatchGetJobEntity API change (#139) ([`5197e57`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/5197e5767a5134e192602ecc85d5d98f0f32f24e))
* include Queue ID in sync_inputs, sync_outputs telemetry (#135) ([`c3579af`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/c3579af41735715e74acfec56b8be87a6995ecac))
* compatibility with BatchGetJobEntity API changes for jobRunAsUser (#133) ([`08d7ba6`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/08d7ba6ebd219e202f545885937d0ed02aee9811))
* rename "updateTime" to "updatedAt" in UpdateWorkerSchedule API request (#131) ([`f607954`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/f607954112b7f1298b95afc3b1dc16322ce6bfbe))
* emit job attachment transfer statistics as telemetry events (#104) ([`ccaa097`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/ccaa09759ed9533e5388fa4ecef60fa17cbe098d))
* rename impersonation options to use run-as nomenclature (#92) ([`5165a4d`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/5165a4d2ade202b4a85a78473f6d9d160bba1f06))
* print versions of 1st party dependencies to worker log (#82) ([`b98be06`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/b98be067266dfdf1f1f52bc3ab3de6eefdd040f8))
* **install**: Adding vfs install path to install parameters (#58) ([`60959c0`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/60959c098eda9bce46f83123b6b0957f6504432e))
* add host metrics logging (#45) ([`1718c57`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1718c575ae73deb5f6a324da78bf7c5f24ab75d8))
* session lifecycle log improvements (#51) ([`f658fff`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/f658fff5c90df32fc0b9d650072b9e32eaf2990c))
* log completed session actions (#49) ([`bb4e3bd`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/bb4e3bd37d69fc09dd75bca54108ccf4232a7013))
* Adds telemetry client calls to worker (#42) ([`1e96738`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1e967381832d45fc173a25dcd8efd0278b206024))
* update to the new job schema ([`9aafbbe`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/9aafbbe57c1c07b19f5db1a6de2d8d135ef0a2ea))
* add --no-install-service to installer and add integration test (#13) ([`4237090`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/4237090ef6ec52e394ad6609f29c99dc6ac3fd94))
* Support Storage Profiles path mapping rules when syncing inputs/outputs (#10) ([`c6e549d`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/c6e549d2ac05b648365a74d188efd3647c89bbca))

### Bug Fixes
* update worker workflows ([`531099e`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/531099ee4b90b3541085f6d84c2e95079c7728a6))
* Cleanup log file before starting host config if the file already exists (#634) ([`6466c4f`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/6466c4fbd509867f877a17af1a4a95693590808b))
* **ASSET_SYNC_JOB_USER_FEATURE**: NonValidInputError failures and uploading files from input job attachment directories (#612) ([`4c12664`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/4c126648a657df83e065c77274c965b8d0ad283e))
* Worker Agent Crashes on corrupted cached credentials (#614) ([`7f1ec05`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/7f1ec05d86035febd68daffa603d8da404b8854a))
* High memory use when running job attachment test cases (#576) ([`b88b8e1`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/b88b8e184ae3b677aac2882afca25accfe27f925))
* unexpected GPU memory configurations crash worker agent (#574) ([`b423bfb`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/b423bfb68e258c2b86e90925669572691ccab2c3))
* worker agent unable to start without EC2 metadata access (#572) ([`5e73148`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/5e7314839a3cd9da7bfa50ab9f4198fcabb5edf4))
* install-deadline-worker on Windows creates session root directory without read and traversal permissions for Users (#563) ([`29e7aee`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/29e7aee77ab362094b219dd5ec20920a1b859078))
* **experimental**: task with step-step dependency upload job inputs as outputs (#529) ([`abe0fb0`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/abe0fb0f2c4b04de1490943502f83061e160d938))
* more robust config file modifications in install-deadline-worker (#512) ([`1060b4b`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1060b4bd29890c0b76ece8665b0415cb5a3303e2))
* worker state file saved on AMI causes multiple instances sharing same worker ID (#527) ([`ec001c9`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/ec001c9830b0fd7639248a2b2bc892787993c5b2))
* skip attachment upload when outputs not modified (#524) ([`972df4e`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/972df4ead8311967ad26844f0445859cae9ae483))
* update log kind to differentiate sync input and sync output (#523) ([`af28588`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/af285880ae66c697534aabae2f28fbc626873fa8))
* increase e2e test instance size (#468) ([`2f7cc57`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/2f7cc57169d710f3da21412ae0f40f5b1e171f05))
* non-user-friendly error when trying to install the worker agent as domain user (#457) ([`15afe89`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/15afe89930f99f92346a4b96806c4c68d76bdbae))
* increase default instance size (#441) ([`e8f0117`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/e8f01178076979210a0a64d079468d142224481b))
* crash when host has multiple NVIDIA GPUs (#435) ([`760118c`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/760118c0ab8157ecc5087fc919f6773b0cd6c376))
* prevent test s3 buckets not being able to be created in some regions (#426) ([`7dfd09b`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/7dfd09b8991cf51adf5c16f54d2ab2ff60e3a965))
* Add job cancellation when test is finish to avoid side effect (#425) ([`2b521a5`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/2b521a5d37726666463e5213f604775c2ea3d058))
* vague error message when no AWS region specified (#413) ([`0d5ccad`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/0d5ccadebab5aca5b562abf6d8032aa79ca51678))
* WindowsPath is not JSON serializable during session cleanup (#412) ([`5d5055c`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/5d5055cf728a98769415a30a923eea057b8d9683))
* Ensure scheduler drain and status update on Windows service shutdown (#408) ([`f269b67`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/f269b67d415e0203a49b9f85bf8b811b345f96e6))
* allow retries to tests (#397) ([`87613eb`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/87613ebf9f1cf6342f43f012378f28ad50357e45))
* Agent Logs to /var/log/messages when running as a service on Linux (#396) ([`b2368ed`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/b2368edeaec80b6c31132195dbdf4579b5e7e225))
* --run-jobs-as-agent-user crashes on windows (#395) ([`6fef296`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/6fef2969ef5cd4eb12adc76eded4587f447c0726))
* install-deadline-worker doesn't create queues persistence dir on Windows (#377) ([`bd40074`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/bd40074f3117d78e2080b01bb439cc1f146091eb))
* posix installer succeeds if agent-user does not already exist (#378) ([`17435b1`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/17435b15941305baf09ac772eeb6723a66ec7902))
* jobRunAsUser always removed in BatchGetJobEntity JobDetails (#349) ([`b6a64de`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/b6a64ded6b725822d097ac9fad8f12c4e63e9388))
* fail on BatchGetJobEntity jobRunAsUser validation with a job user override  (#346) ([`c0dd3b3`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/c0dd3b35db2faef3296277cbf66e3dc42adeb80f))
* install-deadline-worker on Linux assumes agent os group matches username (#345) ([`4ed1136`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/4ed1136e1ed6e5d7cdfcbd9cb5d0848ff4bd316e))
* error due to out-of-range process exit code (#339) ([`7d4ec30`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/7d4ec30f15af952cdcf03d3c28d9ce9608d861ab))
* handle case where BatchGetJobEntity returns no jobRunAsUser (#293) ([`616e16c`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/616e16c293ae544fe948528b485a6892c36bf0a6))
* provide region in queue AWS configuration (#289) ([`efeecfe`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/efeecfe354cdfe321fe96718ed51704e67ab847a))
* stop the running Windows service before re-installation. (#288) ([`0587b60`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/0587b6026622424584e46717561d6ee61879bbba))
* example config file inaccurately documents allow_ec2_instance_profile (#278) ([`1d1ecc1`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1d1ecc165384c6f14ace4465236460ba12b176ee))
* set log file encoding to utf-8 (#267) ([`1008083`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/10080837558bc369c35243b5c15af82d45e35467))
* unhandled exception unloading user profile (#264) ([`62a404b`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/62a404b0d9db8d95e02b4e977d4a343f2444cc00))
* remove time field from structured logs (#263) ([`d246abf`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/d246abf1595d07e5cb99bb9a451d3fb7162baf2f))
* handle OSError when detecting GPU capabilities (#255) ([`677fda6`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/677fda63e51a8c436c47faf9650b147a462b2a31))
* handle IMDS disruptions gracefully (#249) ([`ea6b701`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/ea6b70102add121362da7009724146c604ebfa45))
* return sessionactions if Session is stopped (#252) ([`1230d89`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1230d89152ae72bae77747da32e551dbc92c9c98))
* insufficient Windows ACLs for job user AWS config files (#246) ([`f5e2f52`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/f5e2f52aa747976f15540a6f0da561a0f7faa57d))
* NEVER_ATTEMPTED session actions should not report startedAt or endedAt (#237) ([`99fd7d3`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/99fd7d385dedc25c22aeaecee7247bef3e682fa0))
* improve logging when getting secret (#184) ([`d3e2e0c`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/d3e2e0c863efd2af8b1eeb0a6f3173b7c6b6a23d))
* increasing default password length for windows users (#236) ([`c411c85`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/c411c851395fa6a46a174d9709b3b907dd9796f1))
* change windows logon type from NETWORK to INTERACTIVE (#234) ([`82a5c11`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/82a5c11195102e3334961b4420915feccfc849b0))
* Fail jobs configured to run as worker agent when Admin (#230) ([`7ce01a8`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/7ce01a8731005178a6da964c24870b3fc9d57f03))
* change OpenJD's session root directory to /sessions (#222) ([`3b68342`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/3b68342bc12307e63f84214b310ed616437c1c8e))
* improve error messaging for Windows logon (#219) ([`de23226`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/de232262d503da01f5f1aa974d985555fe51008a))
* **install.sh**: update ownership and permissions for session root directory (#201) ([`230b73c`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/230b73c5c6c472256db68ab43ddd83203889d245))
* complete all actions following unsuccessful actions as NEVER_ATTEMPTED (#190) ([`d266c0f`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/d266c0f9740bd82d4ca85b7de2031e68edfd8b77))
* handle non-existent queue jobRunAsUser on worker host (#176) ([`1049a48`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1049a48f0ff045160f5524eb25c3f97a42114fcb))
* Set shutdown_on_stop value in config file. (#164) ([`858f621`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/858f621e4939b0b5bc32262bc90cc4fa80dd148e))
* Terminating all VFS processes when cleaning up session (#149) ([`50178ed`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/50178ede860949b766f85ef7f3e0c586ce8bc8e9))
* permissions on /var/log/amazon directory (#162) ([`1acfffc`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1acfffc69040061b3e9fa02894e2a7a7cbab204d))
* no longer sigterm agent when running jobs as same user (#161) ([`fe12ad3`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/fe12ad32076a3ce2a87ae84f1dbe46a4fc8c0121))
* don't invert shutdown_on_stop config file setting's meaning (#155) ([`1a7329f`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1a7329f039ad9c164c0ee2c5c05e333462fdf892))
* crash if queue has no user defined (#127) ([`3b62715`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/3b6271590517820e2d187a853fbfa023cf306a09))
* job attachment output upload blocking UpdateWorkerSchedule API requests (#122) ([`f2b3893`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/f2b38939b2b5936979bdbd8d562fd5454de3dfb6))
* OpenJD architecture capability reporting on ARM (#118) ([`73a2877`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/73a287792381542f68138d137086bf7afd8747c0))
* use release environment in release workflow integ tests (#112) ([`3ae3a16`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/3ae3a169ddb3e738bf424597c2156d15714118cb))
* "jobs_run..." -> "run_jobs..." (#93) ([`1cc9f34`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1cc9f3412fc3c2118133560e03705f330d68e168))
* Adding os_user to FileSystemPermissionSettings for use in the deadline vfs (#94) ([`1625ce5`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1625ce51f2691a335bc3a1cd4c06a9a793876698))
* avoid truncating sessionaction logs (#86) ([`47dca3e`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/47dca3e35d332401c4ff365336736717666d0532))
* mock HostMetricsLogger in entrypoint tests (#70) ([`b9df0a9`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/b9df0a91e8bca4c75ac3571e9b4248800d759158))
* use NEVER_ATTEMPTED after session action failures (#74) ([`5060e16`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/5060e16447a35fa8cf543e54f07b43223e710b7e))
* handle CONCURRENT_MODIFICATION conflict from UpdateWorkerSchedule (#69) ([`da4da41`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/da4da414c6268d8081526dcfb542ca4aa4fc30af))
* mock host metrics logger in worker module for tests (#64) ([`0628cd2`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/0628cd2be49031268c94529ad88a05e85e2dc193))
* set RunStepTaskAction end time to asset sync completion time (#11) ([`2fd6c47`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/2fd6c47b18175e44c8593aa31899e67109ebe343))
* respect service's suggested retryAfter when throttled (#39) ([`d83066a`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/d83066adaa7f17990ece7f8e90a026b113bbc1ae))
* add job_run_as_user to integ test (#57) ([`962808f`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/962808fb850df31fcd7827a605d5e331045bc938))
* **job_attachment**: Change osType to rootPathFormat (#37) ([`5a39c25`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/5a39c251919a3bc72f2a1dfb9830f4a5e4a9fc50))
* remove the recursive ownership/permissions changes (#26) ([`1c3a9b5`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1c3a9b54460a33e973305f8d48dfacbf2c237e7e))
* remove old schema workaround (#32) ([`c37bb47`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/c37bb47b818094a90c00c38ffe5b7940fcc6fab3))
* Use status instead of targetStatus in UpdateWorker. (#29) ([`a22e7df`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/a22e7df0dd30e0b9fd4a2ac3f8f495523fd656fb))
* duplicate layers of API request retries and integer overflow in backoff ([`4905915`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/4905915a1d604ae03091d223a638b6c4a9ae0033))
* Fixing name mismatch in testing scripts (#19) ([`20c3b72`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/20c3b72894214d0b08a0188f3cf4f0500b3ffd23))
* use the proper entity key variable (#15) ([`8f6f9b4`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/8f6f9b4ada3f94ff57658908c8ec3310a7297f8c))
* use try/except/finally clause in SyncInputJobAttachmentsAction, to ensure that the update action happens (#12) ([`0d64cbd`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/0d64cbd6a567029e99537369728b3f1aa62b1882))
* Update worker binary to deadline-worker-agent where necessary (#7) ([`044f0fa`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/044f0fa5ce28e9764589373f09c2e07195492764))
* fail installer when worker agent path is not found (#4) ([`f397f80`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/f397f801c2e63e8e8f55432057aa2f71a8f70aed))

## 0.1.0 (2025-05-21)


### Features
* Launch Host Configuration feature (#636) ([`dd2071d`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/dd2071d1d01d6cd811531bc1d689c114a7e760e5))
* **experimental**: add support for chunkInt parameter type ([`4c517b4`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/4c517b4a37c35ee4cc8c1ba79bfc6bc1cb29f250))
* **HOST_CONFIGURATION_FEATURE**: Prevent Windows ACL inheritance for host config script and log and grant full control to Administrators ([`98dfbfc`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/98dfbfc9dbebdb02145c8413a76fe82f45635c58))
* **HOST_CONFIGURATION_FEATURE**: delimit host configuration script with banners in worker logs and shutdown host on failure ([`f08bca8`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/f08bca8656488d9af992b1dca4b4969f5bdf96b6))
* Support running configuration scripts after worker reaches STARTED state (#601) ([`d925c65`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/d925c65a052579675443d004295c2b70f019fe9b))
* configurable session root directory (#513) ([`dd541a1`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/dd541a12eac344e109ca283166f978a20af8439c))
* run job attachment output upload as job user (#495) ([`678f29a`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/678f29a6ae86265b6a0f912cdcc52a2ceccb7b62))
* directly send cancel OS signals on Linux (#479) ([`a0fc35c`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/a0fc35c419bba964ffa5146f8bb65c54064fc929))
* integrate with job attachment download cli as a openjd action run (#476) ([`07abc76`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/07abc76dc9bdd46a7281a6349b1bb7eaaa808810))
* include specific session runtime logs in the worker log (#422) ([`be55928`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/be55928bb55ca361a2900b16f599ccc1f1b03b7c))
* add job user override for windows (#372) ([`84c83bd`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/84c83bdffbce7b44f46668cce3ec36ac596fab5d))
* add success or fail metric on Job Attachment calls (#352) ([`ac1e5e0`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/ac1e5e0d4b7ba8c85ec868c84ee5cabf4980f091))
* add deadline client lib, OpenJD Sessions to boto3 header (#351) ([`51fc0f1`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/51fc0f10b02fde81904b4688e20c91adb83c3c8e))
* differentiate step actions from non-step actions in logs (#292) ([`a6d55e3`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/a6d55e3849cd4c374e91d184ed3ad40bd88d491f))
* public release (#271) ([`ed1e14d`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/ed1e14df818e8161490a5c6b884320eeb7b6832e))
* remove deprecated features (#277) ([`d984094`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/d984094f74b9ad60dd0bc82ec3eb917cda4e138d))
* adds data on action kind and queue length to logs (#266) ([`bb10c47`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/bb10c4758dab094738b23859a3e8aae64fac4850))
* overhaul agent logging to introduce structured logs (#216) ([`abed8c9`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/abed8c95c932f0890eb03f5ed383ce8def3a37dc))
* **installer**: allow ec2 instance profile by default (#259) ([`7e4d947`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/7e4d9474bd96d1d0b7a7ba749acca80d1266b0a3))
* aws config directory managed by agent (#254) ([`2f4fd8a`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/2f4fd8a7a2431f8b4bbbfd92cbc435095be8278b))
* **installer**: detect default AWS region on EC2 (#250) ([`3db8685`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/3db86851bc9bcc9afec33c9fdd1b981897266b12))
* cleanup asset_sync session with os_user (#251) ([`b68922e`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/b68922e37d95c37b3eec88b990d88b7fba60875e))
* **windows-installer**: configure AWS region in Windows service (#242) ([`adf164f`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/adf164ff56b56bc48837012d99bc086b1120193a))
* agent logs contain more verbose API request/response information (#215) ([`6e8e566`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/6e8e566dadfd39c77737ac5243276256f87d492c))
* session cleanup on windows (#212) ([`93f4305`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/93f43053ccd498fd913b31b8aa96c4d43fae7157))
* **windows-installer**: grant and validate agent user permissions (#206) ([`0d8e3de`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/0d8e3de5ee4ccdadffbbc365c2e822ff62efc0fd))
* Add telemetry event for uncaught exceptions (#203) ([`9a17a07`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/9a17a0786fe47b1e0ad0d69ee55c0746823a95a5))
* retool scale-in behaviour (#193) ([`40390e9`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/40390e92d3e799f5299233b6d030a9e66582e18c))
* windows service (#207) ([`1d97970`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1d979709941e2c2b116cb7932d664a64584a95d4))
* **windows-installer**: add client telemetry opt out option (#210) ([`7551869`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/7551869124f8a7ef219888b52e472f632ec68b0d))
* windows support (#205) ([`80e8ec4`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/80e8ec423ced2130792d95af7690bb9b64b77565))
* change OpenJD's session directory path, and add `--retain-session-dir` command option (#196) ([`091608c`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/091608c65b50e6fecac94dfff4e2f088c1f49926))
* Add job and session metadata to the environment of a job (#189) ([`92b6d17`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/92b6d17e91cfd19981f0e19d66c47e614150eb44))
* Cancel Job Attachments session action when transfer rates drop below threshold (#143) ([`c49bbb4`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/c49bbb498949e3ed2b469714717018669134d5c2))
* report action timeout as failed with timeout message (#165) ([`ff36123`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/ff3612387f9b010359480367bea62f67235be3aa))
* provision ownership on /var/lib/deadline/credentials directory (#145) ([`3b3e7af`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/3b3e7af471ab4f7947163f8978d2d9de0baad091))
* adds compatibility with upcoming BatchGetJobEntity API change (#139) ([`5197e57`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/5197e5767a5134e192602ecc85d5d98f0f32f24e))
* include Queue ID in sync_inputs, sync_outputs telemetry (#135) ([`c3579af`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/c3579af41735715e74acfec56b8be87a6995ecac))
* compatibility with BatchGetJobEntity API changes for jobRunAsUser (#133) ([`08d7ba6`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/08d7ba6ebd219e202f545885937d0ed02aee9811))
* rename "updateTime" to "updatedAt" in UpdateWorkerSchedule API request (#131) ([`f607954`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/f607954112b7f1298b95afc3b1dc16322ce6bfbe))
* emit job attachment transfer statistics as telemetry events (#104) ([`ccaa097`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/ccaa09759ed9533e5388fa4ecef60fa17cbe098d))
* rename impersonation options to use run-as nomenclature (#92) ([`5165a4d`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/5165a4d2ade202b4a85a78473f6d9d160bba1f06))
* print versions of 1st party dependencies to worker log (#82) ([`b98be06`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/b98be067266dfdf1f1f52bc3ab3de6eefdd040f8))
* **install**: Adding vfs install path to install parameters (#58) ([`60959c0`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/60959c098eda9bce46f83123b6b0957f6504432e))
* add host metrics logging (#45) ([`1718c57`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1718c575ae73deb5f6a324da78bf7c5f24ab75d8))
* session lifecycle log improvements (#51) ([`f658fff`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/f658fff5c90df32fc0b9d650072b9e32eaf2990c))
* log completed session actions (#49) ([`bb4e3bd`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/bb4e3bd37d69fc09dd75bca54108ccf4232a7013))
* Adds telemetry client calls to worker (#42) ([`1e96738`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1e967381832d45fc173a25dcd8efd0278b206024))
* update to the new job schema ([`9aafbbe`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/9aafbbe57c1c07b19f5db1a6de2d8d135ef0a2ea))
* add --no-install-service to installer and add integration test (#13) ([`4237090`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/4237090ef6ec52e394ad6609f29c99dc6ac3fd94))
* Support Storage Profiles path mapping rules when syncing inputs/outputs (#10) ([`c6e549d`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/c6e549d2ac05b648365a74d188efd3647c89bbca))

### Bug Fixes
* Cleanup log file before starting host config if the file already exists (#634) ([`6466c4f`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/6466c4fbd509867f877a17af1a4a95693590808b))
* **ASSET_SYNC_JOB_USER_FEATURE**: NonValidInputError failures and uploading files from input job attachment directories (#612) ([`4c12664`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/4c126648a657df83e065c77274c965b8d0ad283e))
* Worker Agent Crashes on corrupted cached credentials (#614) ([`7f1ec05`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/7f1ec05d86035febd68daffa603d8da404b8854a))
* High memory use when running job attachment test cases (#576) ([`b88b8e1`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/b88b8e184ae3b677aac2882afca25accfe27f925))
* unexpected GPU memory configurations crash worker agent (#574) ([`b423bfb`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/b423bfb68e258c2b86e90925669572691ccab2c3))
* worker agent unable to start without EC2 metadata access (#572) ([`5e73148`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/5e7314839a3cd9da7bfa50ab9f4198fcabb5edf4))
* install-deadline-worker on Windows creates session root directory without read and traversal permissions for Users (#563) ([`29e7aee`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/29e7aee77ab362094b219dd5ec20920a1b859078))
* **experimental**: task with step-step dependency upload job inputs as outputs (#529) ([`abe0fb0`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/abe0fb0f2c4b04de1490943502f83061e160d938))
* more robust config file modifications in install-deadline-worker (#512) ([`1060b4b`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1060b4bd29890c0b76ece8665b0415cb5a3303e2))
* worker state file saved on AMI causes multiple instances sharing same worker ID (#527) ([`ec001c9`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/ec001c9830b0fd7639248a2b2bc892787993c5b2))
* skip attachment upload when outputs not modified (#524) ([`972df4e`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/972df4ead8311967ad26844f0445859cae9ae483))
* update log kind to differentiate sync input and sync output (#523) ([`af28588`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/af285880ae66c697534aabae2f28fbc626873fa8))
* increase e2e test instance size (#468) ([`2f7cc57`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/2f7cc57169d710f3da21412ae0f40f5b1e171f05))
* non-user-friendly error when trying to install the worker agent as domain user (#457) ([`15afe89`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/15afe89930f99f92346a4b96806c4c68d76bdbae))
* increase default instance size (#441) ([`e8f0117`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/e8f01178076979210a0a64d079468d142224481b))
* crash when host has multiple NVIDIA GPUs (#435) ([`760118c`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/760118c0ab8157ecc5087fc919f6773b0cd6c376))
* prevent test s3 buckets not being able to be created in some regions (#426) ([`7dfd09b`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/7dfd09b8991cf51adf5c16f54d2ab2ff60e3a965))
* Add job cancellation when test is finish to avoid side effect (#425) ([`2b521a5`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/2b521a5d37726666463e5213f604775c2ea3d058))
* vague error message when no AWS region specified (#413) ([`0d5ccad`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/0d5ccadebab5aca5b562abf6d8032aa79ca51678))
* WindowsPath is not JSON serializable during session cleanup (#412) ([`5d5055c`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/5d5055cf728a98769415a30a923eea057b8d9683))
* Ensure scheduler drain and status update on Windows service shutdown (#408) ([`f269b67`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/f269b67d415e0203a49b9f85bf8b811b345f96e6))
* allow retries to tests (#397) ([`87613eb`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/87613ebf9f1cf6342f43f012378f28ad50357e45))
* Agent Logs to /var/log/messages when running as a service on Linux (#396) ([`b2368ed`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/b2368edeaec80b6c31132195dbdf4579b5e7e225))
* --run-jobs-as-agent-user crashes on windows (#395) ([`6fef296`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/6fef2969ef5cd4eb12adc76eded4587f447c0726))
* install-deadline-worker doesn't create queues persistence dir on Windows (#377) ([`bd40074`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/bd40074f3117d78e2080b01bb439cc1f146091eb))
* posix installer succeeds if agent-user does not already exist (#378) ([`17435b1`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/17435b15941305baf09ac772eeb6723a66ec7902))
* jobRunAsUser always removed in BatchGetJobEntity JobDetails (#349) ([`b6a64de`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/b6a64ded6b725822d097ac9fad8f12c4e63e9388))
* fail on BatchGetJobEntity jobRunAsUser validation with a job user override  (#346) ([`c0dd3b3`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/c0dd3b35db2faef3296277cbf66e3dc42adeb80f))
* install-deadline-worker on Linux assumes agent os group matches username (#345) ([`4ed1136`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/4ed1136e1ed6e5d7cdfcbd9cb5d0848ff4bd316e))
* error due to out-of-range process exit code (#339) ([`7d4ec30`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/7d4ec30f15af952cdcf03d3c28d9ce9608d861ab))
* handle case where BatchGetJobEntity returns no jobRunAsUser (#293) ([`616e16c`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/616e16c293ae544fe948528b485a6892c36bf0a6))
* provide region in queue AWS configuration (#289) ([`efeecfe`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/efeecfe354cdfe321fe96718ed51704e67ab847a))
* stop the running Windows service before re-installation. (#288) ([`0587b60`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/0587b6026622424584e46717561d6ee61879bbba))
* example config file inaccurately documents allow_ec2_instance_profile (#278) ([`1d1ecc1`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1d1ecc165384c6f14ace4465236460ba12b176ee))
* set log file encoding to utf-8 (#267) ([`1008083`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/10080837558bc369c35243b5c15af82d45e35467))
* unhandled exception unloading user profile (#264) ([`62a404b`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/62a404b0d9db8d95e02b4e977d4a343f2444cc00))
* remove time field from structured logs (#263) ([`d246abf`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/d246abf1595d07e5cb99bb9a451d3fb7162baf2f))
* handle OSError when detecting GPU capabilities (#255) ([`677fda6`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/677fda63e51a8c436c47faf9650b147a462b2a31))
* handle IMDS disruptions gracefully (#249) ([`ea6b701`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/ea6b70102add121362da7009724146c604ebfa45))
* return sessionactions if Session is stopped (#252) ([`1230d89`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1230d89152ae72bae77747da32e551dbc92c9c98))
* insufficient Windows ACLs for job user AWS config files (#246) ([`f5e2f52`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/f5e2f52aa747976f15540a6f0da561a0f7faa57d))
* NEVER_ATTEMPTED session actions should not report startedAt or endedAt (#237) ([`99fd7d3`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/99fd7d385dedc25c22aeaecee7247bef3e682fa0))
* improve logging when getting secret (#184) ([`d3e2e0c`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/d3e2e0c863efd2af8b1eeb0a6f3173b7c6b6a23d))
* increasing default password length for windows users (#236) ([`c411c85`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/c411c851395fa6a46a174d9709b3b907dd9796f1))
* change windows logon type from NETWORK to INTERACTIVE (#234) ([`82a5c11`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/82a5c11195102e3334961b4420915feccfc849b0))
* Fail jobs configured to run as worker agent when Admin (#230) ([`7ce01a8`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/7ce01a8731005178a6da964c24870b3fc9d57f03))
* change OpenJD's session root directory to /sessions (#222) ([`3b68342`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/3b68342bc12307e63f84214b310ed616437c1c8e))
* improve error messaging for Windows logon (#219) ([`de23226`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/de232262d503da01f5f1aa974d985555fe51008a))
* **install.sh**: update ownership and permissions for session root directory (#201) ([`230b73c`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/230b73c5c6c472256db68ab43ddd83203889d245))
* complete all actions following unsuccessful actions as NEVER_ATTEMPTED (#190) ([`d266c0f`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/d266c0f9740bd82d4ca85b7de2031e68edfd8b77))
* handle non-existent queue jobRunAsUser on worker host (#176) ([`1049a48`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1049a48f0ff045160f5524eb25c3f97a42114fcb))
* Set shutdown_on_stop value in config file. (#164) ([`858f621`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/858f621e4939b0b5bc32262bc90cc4fa80dd148e))
* Terminating all VFS processes when cleaning up session (#149) ([`50178ed`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/50178ede860949b766f85ef7f3e0c586ce8bc8e9))
* permissions on /var/log/amazon directory (#162) ([`1acfffc`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1acfffc69040061b3e9fa02894e2a7a7cbab204d))
* no longer sigterm agent when running jobs as same user (#161) ([`fe12ad3`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/fe12ad32076a3ce2a87ae84f1dbe46a4fc8c0121))
* don't invert shutdown_on_stop config file setting's meaning (#155) ([`1a7329f`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1a7329f039ad9c164c0ee2c5c05e333462fdf892))
* crash if queue has no user defined (#127) ([`3b62715`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/3b6271590517820e2d187a853fbfa023cf306a09))
* job attachment output upload blocking UpdateWorkerSchedule API requests (#122) ([`f2b3893`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/f2b38939b2b5936979bdbd8d562fd5454de3dfb6))
* OpenJD architecture capability reporting on ARM (#118) ([`73a2877`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/73a287792381542f68138d137086bf7afd8747c0))
* use release environment in release workflow integ tests (#112) ([`3ae3a16`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/3ae3a169ddb3e738bf424597c2156d15714118cb))
* "jobs_run..." -> "run_jobs..." (#93) ([`1cc9f34`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1cc9f3412fc3c2118133560e03705f330d68e168))
* Adding os_user to FileSystemPermissionSettings for use in the deadline vfs (#94) ([`1625ce5`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1625ce51f2691a335bc3a1cd4c06a9a793876698))
* avoid truncating sessionaction logs (#86) ([`47dca3e`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/47dca3e35d332401c4ff365336736717666d0532))
* mock HostMetricsLogger in entrypoint tests (#70) ([`b9df0a9`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/b9df0a91e8bca4c75ac3571e9b4248800d759158))
* use NEVER_ATTEMPTED after session action failures (#74) ([`5060e16`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/5060e16447a35fa8cf543e54f07b43223e710b7e))
* handle CONCURRENT_MODIFICATION conflict from UpdateWorkerSchedule (#69) ([`da4da41`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/da4da414c6268d8081526dcfb542ca4aa4fc30af))
* mock host metrics logger in worker module for tests (#64) ([`0628cd2`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/0628cd2be49031268c94529ad88a05e85e2dc193))
* set RunStepTaskAction end time to asset sync completion time (#11) ([`2fd6c47`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/2fd6c47b18175e44c8593aa31899e67109ebe343))
* respect service's suggested retryAfter when throttled (#39) ([`d83066a`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/d83066adaa7f17990ece7f8e90a026b113bbc1ae))
* add job_run_as_user to integ test (#57) ([`962808f`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/962808fb850df31fcd7827a605d5e331045bc938))
* **job_attachment**: Change osType to rootPathFormat (#37) ([`5a39c25`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/5a39c251919a3bc72f2a1dfb9830f4a5e4a9fc50))
* remove the recursive ownership/permissions changes (#26) ([`1c3a9b5`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/1c3a9b54460a33e973305f8d48dfacbf2c237e7e))
* remove old schema workaround (#32) ([`c37bb47`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/c37bb47b818094a90c00c38ffe5b7940fcc6fab3))
* Use status instead of targetStatus in UpdateWorker. (#29) ([`a22e7df`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/a22e7df0dd30e0b9fd4a2ac3f8f495523fd656fb))
* duplicate layers of API request retries and integer overflow in backoff ([`4905915`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/4905915a1d604ae03091d223a638b6c4a9ae0033))
* Fixing name mismatch in testing scripts (#19) ([`20c3b72`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/20c3b72894214d0b08a0188f3cf4f0500b3ffd23))
* use the proper entity key variable (#15) ([`8f6f9b4`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/8f6f9b4ada3f94ff57658908c8ec3310a7297f8c))
* use try/except/finally clause in SyncInputJobAttachmentsAction, to ensure that the update action happens (#12) ([`0d64cbd`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/0d64cbd6a567029e99537369728b3f1aa62b1882))
* Update worker binary to deadline-worker-agent where necessary (#7) ([`044f0fa`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/044f0fa5ce28e9764589373f09c2e07195492764))
* fail installer when worker agent path is not found (#4) ([`f397f80`](https://github.com/moorec-aws/deadline-cloud-worker-agent/commit/f397f801c2e63e8e8f55432057aa2f71a8f70aed))

## 0.28.6 (2025-05-01)


### Experimental

These changes are experimental and only available through the use of feature flags

* HOST_CONFIGURATION_FEATURE - Prevent Windows ACL inheritance for host config script and log and grant full control to Administrators ([`98dfbfc`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/98dfbfc9dbebdb02145c8413a76fe82f45635c58))
* HOST_CONFIGURATION_FEATURE - delimit host configuration script with banners in worker logs and shutdown host on failure ([`f08bca8`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/f08bca8656488d9af992b1dca4b4969f5bdf96b6))


## 0.28.5 (2025-04-11)


### Experimental

These changes are experimental and only available through the use of feature flags

* HOST_CONFIGURATION_FEATURE - run admin host configuration scripts once worker becomes STARTED (#601) ([`d925c65`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/d925c65a052579675443d004295c2b70f019fe9b))


## 0.28.4 (2025-04-03)




## 0.28.3 (2025-03-13)



### Bug Fixes
* unexpected GPU memory configurations crash worker agent (#574) ([`b423bfb`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/b423bfb68e258c2b86e90925669572691ccab2c3))

## 0.28.2 (2025-03-11)



### Bug Fixes
* worker agent unable to start without EC2 metadata access (#572) ([`5e73148`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/5e7314839a3cd9da7bfa50ab9f4198fcabb5edf4))

## 0.28.1 (2025-03-05)



### Bug Fixes
* install-deadline-worker on Windows creates session root directory without read and traversal permissions for Users (#563) ([`29e7aee`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/29e7aee77ab362094b219dd5ec20920a1b859078))

### Experimental

These changes are experimental and only available through the use of feature flags

* ASSET_SYNC_JOB_USER_FEATURE - **fix**: task with step-step dependency upload job inputs as outputs (#529) ([`abe0fb0`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/abe0fb0f2c4b04de1490943502f83061e160d938))


## 0.28.0 (2025-02-27)
**This Release has been pulled from PyPI. The use of this release contains a regression in default permissions for the session directory on Windows. Downgrade to 0.27.5 or upgrade to the next release if available.**

### BREAKING CHANGES
* A defect was fixed in the OpenJobDescription specification ([OpenJobDescription/openjd-specifications#70](https://github.com/OpenJobDescription/openjd-specifications/issues/70)) which causes a breaking change to Worker Agent behaviour. Environment exits previously had no default timeout and they now have a default timeout of 5 minutes. To have long-running environment exit actions, job templates can specify a large timeout value when defining environment exit actions in a job or environment template.

### Features
* configurable session root directory (#513) ([`dd541a1`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/dd541a12eac344e109ca283166f978a20af8439c))

### Bug Fixes
* more robust config file modifications in install-deadline-worker (#512) ([`1060b4b`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/1060b4bd29890c0b76ece8665b0415cb5a3303e2))
* worker state file saved on AMI causes multiple instances sharing same worker ID (#527) ([`ec001c9`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/ec001c9830b0fd7639248a2b2bc892787993c5b2))
* skip attachment upload when outputs not modified (#524) ([`972df4e`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/972df4ead8311967ad26844f0445859cae9ae483))
* update log kind to differentiate sync input and sync output (#523) ([`af28588`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/af285880ae66c697534aabae2f28fbc626873fa8))

## 0.27.5 (2024-12-14)


### Features
* directly send cancel OS signals on Linux (#479) ([`a0fc35c`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/a0fc35c419bba964ffa5146f8bb65c54064fc929))

### Bug Fixes
* increase e2e test instance size (#468) ([`2f7cc57`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/2f7cc57169d710f3da21412ae0f40f5b1e171f05))

### Experimental

These changes are experimental and only available through the use of feature flags

* ASSET_SYNC_JOB_USER_FEATURE - run job attachment output upload as job user (#495) ([`678f29a`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/678f29a6ae86265b6a0f912cdcc52a2ceccb7b62))
* ASSET_SYNC_JOB_USER_FEATURE - integrate with job attachment download cli as a openjd action run (#476) ([`07abc76`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/07abc76dc9bdd46a7281a6349b1bb7eaaa808810))

## 0.27.4 (2024-10-30)


### Features
* include specific session runtime logs in the worker log (#422) ([`be55928`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/be55928bb55ca361a2900b16f599ccc1f1b03b7c))

### Bug Fixes
* non-user-friendly error when trying to install the worker agent as domain user (#457) ([`15afe89`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/15afe89930f99f92346a4b96806c4c68d76bdbae))

## 0.27.3 (2024-10-17)



### Bug Fixes
* crash on startup when host has multiple NVIDIA GPUs (#435) ([`760118c`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/760118c0ab8157ecc5087fc919f6773b0cd6c376))
* vague error message when no AWS region specified (#413) ([`0d5ccad`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/0d5ccadebab5aca5b562abf6d8032aa79ca51678))
* WindowsPath is not JSON serializable during session cleanup (#412) ([`5d5055c`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/5d5055cf728a98769415a30a923eea057b8d9683))
* Ensure scheduler drain and status update on Windows service shutdown (#408) ([`f269b67`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/f269b67d415e0203a49b9f85bf8b811b345f96e6))
* Agent logs to `/var/log/messages` when running as a service on Linux (#396) ([`b2368ed`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/b2368edeaec80b6c31132195dbdf4579b5e7e225))
* `--run-jobs-as-agent-user` crashes on windows (#395) ([`6fef296`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/6fef2969ef5cd4eb12adc76eded4587f447c0726))

## 0.27.2 (2024-08-13)


### Features
* add job user override for windows (#372) ([`84c83bd`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/84c83bdffbce7b44f46668cce3ec36ac596fab5d))
* add success or fail metric on Job Attachment calls (#352) ([`ac1e5e0`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/ac1e5e0d4b7ba8c85ec868c84ee5cabf4980f091))
* add deadline client lib, OpenJD Sessions to boto3 header (#351) ([`51fc0f1`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/51fc0f10b02fde81904b4688e20c91adb83c3c8e))

### Bug Fixes
* install-deadline-worker doesn't create queues persistence dir on Windows (#377) ([`bd40074`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/bd40074f3117d78e2080b01bb439cc1f146091eb))
* posix installer succeeds if agent-user does not already exist (#378) ([`17435b1`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/17435b15941305baf09ac772eeb6723a66ec7902))
* jobRunAsUser always removed in BatchGetJobEntity JobDetails (#349) ([`b6a64de`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/b6a64ded6b725822d097ac9fad8f12c4e63e9388))
* fail on BatchGetJobEntity jobRunAsUser validation with a job user override  (#346) ([`c0dd3b3`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/c0dd3b35db2faef3296277cbf66e3dc42adeb80f))
* install-deadline-worker on Linux assumes agent os group matches username (#345) ([`4ed1136`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/4ed1136e1ed6e5d7cdfcbd9cb5d0848ff4bd316e))
* error due to out-of-range process exit code (#339) ([`7d4ec30`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/7d4ec30f15af952cdcf03d3c28d9ce9608d861ab))

## 0.27.1 (2024-05-01)

### Dependencies
* update deadline requirement from ==0.47.* to ==0.48.* (#306) ([`01326f7`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/01326f78a93f76386b4a0ef8253909127726c66f))


## 0.27.0 (2024-04-10)

### BREAKING CHANGES
* differentiate step actions from non-step actions in logs (#292) ([`a6d55e3`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/a6d55e3849cd4c374e91d184ed3ad40bd88d491f))


### Bug Fixes
* handle case where BatchGetJobEntity returns no jobRunAsUser (#293) ([`616e16c`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/616e16c293ae544fe948528b485a6892c36bf0a6))

## 0.26.1 (2024-04-03)



### Bug Fixes
* provide region in queue AWS configuration (#289) ([`efeecfe`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/efeecfe354cdfe321fe96718ed51704e67ab847a))
* stop the running Windows service before re-installation. (#288) ([`0587b60`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/0587b6026622424584e46717561d6ee61879bbba))

## 0.26.0 (2024-04-02)

### BREAKING CHANGES
* public release (#271) ([`ed1e14d`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/ed1e14df818e8161490a5c6b884320eeb7b6832e))
* remove deprecated features (#277) ([`d984094`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/d984094f74b9ad60dd0bc82ec3eb917cda4e138d))


### Bug Fixes
* example config file inaccurately documents allow_ec2_instance_profile (#278) ([`1d1ecc1`](https://github.com/aws-deadline/deadline-cloud-worker-agent/commit/1d1ecc165384c6f14ace4465236460ba12b176ee))

## 0.25.2 (2024-03-29)




## 0.25.1 (2024-03-28)


### Features
* adds data on action kind and queue length to logs (#266) ([`bb10c47`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/bb10c4758dab094738b23859a3e8aae64fac4850))

### Bug Fixes
* agent not logging events with emojis on Windows due to default encoding (#267) ([`1008083`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/10080837558bc369c35243b5c15af82d45e35467))

## 0.25.0 (2024-03-27)

### BREAKING CHANGES
* remove time field from structured logs (#263) ([`d246abf`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/d246abf1595d07e5cb99bb9a451d3fb7162baf2f))


### Bug Fixes
* unhandled exception unloading user profile (#264) ([`62a404b`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/62a404b0d9db8d95e02b4e977d4a343f2444cc00))

## 0.24.0 (2024-03-26)

### BREAKING CHANGES
* overhaul agent logging to introduce structured logs (#216) ([`abed8c9`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/abed8c95c932f0890eb03f5ed383ce8def3a37dc))
* **installer**: allow ec2 instance profile by default (#259) ([`7e4d947`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/7e4d9474bd96d1d0b7a7ba749acca80d1266b0a3))
* **installer**: detect default AWS region on EC2 (#250) ([`3db8685`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/3db86851bc9bcc9afec33c9fdd1b981897266b12))

### Features
* aws config directory managed by agent (#254) ([`2f4fd8a`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/2f4fd8a7a2431f8b4bbbfd92cbc435095be8278b))

### Bug Fixes
* handle OSError when detecting GPU capabilities (#255) ([`677fda6`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/677fda63e51a8c436c47faf9650b147a462b2a31))
* handle IMDS disruptions gracefully (#249) ([`ea6b701`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/ea6b70102add121362da7009724146c604ebfa45))

## 0.23.1 (2024-03-23)


### Features
* cleanup asset_sync session with os_user (#251) ([`b68922e`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/b68922e37d95c37b3eec88b990d88b7fba60875e))
* **windows-installer**: configure AWS region in Windows service (#242) ([`adf164f`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/adf164ff56b56bc48837012d99bc086b1120193a))

### Bug Fixes
* return sessionactions if Session is stopped (#252) ([`1230d89`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/1230d89152ae72bae77747da32e551dbc92c9c98))
* insufficient Windows ACLs for job user AWS config files (#246) ([`f5e2f52`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/f5e2f52aa747976f15540a6f0da561a0f7faa57d))

## 0.23.0 (2024-03-21)

### BREAKING CHANGES
* Fail jobs configured to run as worker agent on Windows (#230) ([`7ce01a8`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/7ce01a8731005178a6da964c24870b3fc9d57f03))

### Features
* agent logs contain more verbose API request/response information (#215) ([`6e8e566`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/6e8e566dadfd39c77737ac5243276256f87d492c))
* session cleanup on windows (#212) ([`93f4305`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/93f43053ccd498fd913b31b8aa96c4d43fae7157))
* **windows-installer**: grant and validate agent user permissions (#206) ([`0d8e3de`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/0d8e3de5ee4ccdadffbbc365c2e822ff62efc0fd))
* Add telemetry event for uncaught exceptions (#203) ([`9a17a07`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/9a17a0786fe47b1e0ad0d69ee55c0746823a95a5))

### Bug Fixes
* NEVER_ATTEMPTED session actions should not report startedAt or endedAt (#237) ([`99fd7d3`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/99fd7d385dedc25c22aeaecee7247bef3e682fa0))
* improve logging when getting secret (#184) ([`d3e2e0c`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/d3e2e0c863efd2af8b1eeb0a6f3173b7c6b6a23d))
* increasing default password length for windows users (#236) ([`c411c85`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/c411c851395fa6a46a174d9709b3b907dd9796f1))
* change windows logon type from NETWORK to INTERACTIVE (#234) ([`82a5c11`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/82a5c11195102e3334961b4420915feccfc849b0))

## 0.22.1 (2024-03-19)

### Bug Fixes
* change OpenJD&#39;s session root directory to /sessions (#222) ([`3b68342`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/3b68342bc12307e63f84214b310ed616437c1c8e))

## 0.22.0 (2024-03-18)

### BREAKING CHANGES
* retool scale-in behaviour (#193) ([`40390e9`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/40390e92d3e799f5299233b6d030a9e66582e18c))

### Features
* windows service (#207) ([`1d97970`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/1d979709941e2c2b116cb7932d664a64584a95d4))
* **windows-installer**: add client telemetry opt out option (#210) ([`7551869`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/7551869124f8a7ef219888b52e472f632ec68b0d))
* windows support (#205) ([`80e8ec4`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/80e8ec423ced2130792d95af7690bb9b64b77565))
* change OpenJD&#39;s session directory path, and add `--retain-session-dir` command option (#196) ([`091608c`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/091608c65b50e6fecac94dfff4e2f088c1f49926))

### Bug Fixes
* improve error messaging for Windows logon (#219) ([`de23226`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/de232262d503da01f5f1aa974d985555fe51008a))
* **install.sh**: update ownership and permissions for session root directory (#201) ([`230b73c`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/230b73c5c6c472256db68ab43ddd83203889d245))

## 0.21.2 (2024-03-07)


### Features
* Add job and session metadata to the environment of a job (#189) ([`92b6d17`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/92b6d17e91cfd19981f0e19d66c47e614150eb44))

### Bug Fixes
* complete all actions following unsuccessful actions as NEVER_ATTEMPTED (#190) ([`d266c0f`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/d266c0f9740bd82d4ca85b7de2031e68edfd8b77))

## 0.21.1 (2024-02-28)


### Features
* Cancel Job Attachments session action when transfer rates drop below threshold (#143) ([`c49bbb4`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/c49bbb498949e3ed2b469714717018669134d5c2))

### Bug Fixes
* handle non-existent queue jobRunAsUser on worker host (#176) ([`1049a48`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/1049a48f0ff045160f5524eb25c3f97a42114fcb))

## 0.21.0 (2024-02-23)

### BREAKING CHANGES
* Terminating all VFS processes when cleaning up session (#149) ([`50178ed`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/50178ede860949b766f85ef7f3e0c586ce8bc8e9))

### Features
* report action timeout as failed with timeout message (#165) ([`ff36123`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/ff3612387f9b010359480367bea62f67235be3aa))
* provision ownership on /var/lib/deadline/credentials directory (#145) ([`3b3e7af`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/3b3e7af471ab4f7947163f8978d2d9de0baad091))

### Bug Fixes
* Set shutdown_on_stop value in config file. (#164) ([`858f621`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/858f621e4939b0b5bc32262bc90cc4fa80dd148e))
* permissions on /var/log/amazon directory (#162) ([`1acfffc`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/1acfffc69040061b3e9fa02894e2a7a7cbab204d))
* no longer sigterm agent when running jobs as same user (#161) ([`fe12ad3`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/fe12ad32076a3ce2a87ae84f1dbe46a4fc8c0121))
* don&#39;t invert shutdown_on_stop config file setting&#39;s meaning (#155) ([`1a7329f`](https://github.com/casillas2/deadline-cloud-worker-agent/commit/1a7329f039ad9c164c0ee2c5c05e333462fdf892))

