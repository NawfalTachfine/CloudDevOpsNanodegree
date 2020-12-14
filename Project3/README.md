# Project 3: Give Your Application Auto-Deploy Superpowers

## I. Selling CI/CD to your Team/Organization

+ [Continous Delivery Presentation](presentation.pdf)

## II. Deploying Working, Trustworthy Software

### Utilize Deployment Strategies to design and build CI/CD pipelines that support Continuous Delivery processes

+ [Project Code (URL01)](https://github.com/NawfalTachfine/UdaPeopleCICD)
  + [Build Jobs that failed because of compile errors (SCREENSHOT01)](assets/screenshot_01.pdf).
  + Failed unit tests for the [front-end (SCREENSHOT02-1)](assets/screenshot_02_1.pdf) and the [back-end (SCREENSHOT02-2)](assets/screenshot_02_2.pdf).
  + [Failure because of vulnerable packages (SCREENSHOT03)](assets/screenshot_03.pdf).
  + [An alert from one of your failed builds (SCREENSHOT04)](assets/screenshot_04.pdf).

### Utilize a configuration management tool to accomplish deployment to cloud-based servers

+ [Console output of a smoke test job that is failing appropriately. (SCREENSHOT06)](assets/screenshot_06.pdf)
+ [Console output of a successful rollback after a failed smoke test. (SCREENSHOT07)](assets/screenshot_07.pdf)
+ [Console output of successful promotion of new version to production in CloudFront. (SCREENSHOT08)](assets/screenshot_08.pdf)
+ [Console output of successful cleanup job that removes old S3 bucket and EC2 instance. (SCREENSHOT09)](assets/screenshot_09.pdf)
+ Evidence that deploy jobs only happen on master branch: [non-master pipeline (SCREENSHOT10-1)](assets/screenshot_10_1.pdf), master pipeline ([SCREENSHOT10-2](assets/screenshot_10_2.pdf), [SCREENSHOT10-3](assets/screenshot_10_3.pdf))
+ Evidence of deployed and functioning front-end application in an [S3 bucket](https://udapeople-7e280a7.s3.eu-west-3.amazonaws.com/index.html) and in [CloudFront](d20fyhn4egfhdk.cloudfront.net).
+ [Evidence of healthy back-end application (URL04)](ec2-15-237-62-197.eu-west-3.compute.amazonaws.com)

---

## III. Turn Errors into Sirens

+ [Evidence of Prometheus Server (URL05)](www.google.com)
+ [Evidence that Prometheus is monitoring memory, cpu and disk usage of EC2 instances (SCREENSHOT11)](assets/screenshot_11.pdf)
+ [Evidence that Prometheus and AlertManager send alerts when certain conditions exist in the EC2 instance (SCREENSHOT12)](assets/screenshot_12.pdf)
