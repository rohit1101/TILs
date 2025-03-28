## TIL

> Created this repo for tracking my daily learning & inspired by https://github.com/jbranchaud/til

[use case of meta element]: https://web.dev/learn/design/intro/#a-meta-element-for-viewport
[component stack trace]: https://reactjs.org/blog/2017/07/26/error-handling-in-react-16.html#component-stack-traces
[reference links]: https://www.markdownguide.org/basic-syntax/#reference-style-links
[usecases of media queries]: https://web.dev/learn/design/media-queries/#target-different-types-of-output
[why logical properties ?]: https://web.dev/learn/design/internationalization/#logical-properties
[solution]: https://github.com/strapi/strapi/issues/4289
[modify media type on strapi]: <img width="920" alt="image" src="https://user-images.githubusercontent.com/37110560/157438193-20d57f6e-0f2f-4147-b0eb-8c5f5bf9ef08.png">
[flexbox align-content]: https://stackoverflow.com/a/45713137
[deconstruted pancake layout]: https://web.dev/one-line-layouts/#02.-the-deconstructed-pancake:-flex:-lessgrowgreater-lessshrinkgreater-lessbasewidthgreater
[solution]: https://github.com/ohmyzsh/ohmyzsh/issues/6257
[gif]: https://user-images.githubusercontent.com/37110560/169641930-440d82d0-3226-4acd-99b6-ca9eb65543c1.mov
[port-forwarding]: https://kubernetes.io/docs/tasks/access-application-cluster/port-forward-access-application-cluster/#forward-a-local-port-to-a-port-on-the-pod
[sonar-scanner-command]: https://docs.sonarsource.com/sonarqube/latest/analyzing-source-code/scanners/sonarscanner-for-npm/using-the-sonarscanner-for-npm/#command-line
[running docker as non-root user]: https://docs.docker.com/engine/install/linux-postinstall/
[clean up container after exit]: https://docs.docker.com/reference/cli/docker/container/run/#rm
[command for cloning a specific branch on git]: https://stackoverflow.com/a/1911126
[docker compose down]: https://docs.docker.com/reference/cli/docker/compose/down/
[clear terminal]: https://askubuntu.com/questions/25077/how-to-really-clear-the-terminal
[Perfect Forward Secercy]: https://www.vmware.com/topics/perfect-forward-secrecy
[sar command]: https://docs.redhat.com/en/documentation/red_hat_enterprise_linux/4/html/introduction_to_system_administration/s3-resource-tools-sar-sar#s4-resource-tools-sar-reading
[spanner CAP Theorem]: https://cloud.google.com/blog/products/databases/inside-cloud-spanner-and-the-cap-theorem
[nmcli]: https://ubuntu.com/core/docs/networkmanager/configure-wifi-connections
[app runner]: https://docs.aws.amazon.com/apprunner/latest/dg/getting-started.html

| Date        | What did i learn | From where did i learn | 
| ----------- | ---------------- | ---------------------- |
| 10-02-2022  | Learnt why meta element is being used in HTML | [use case of meta element]  |
| 11-02-2022  | Learnt how to fix React bugs using component stack trace | [component stack trace] |
| 12-02-2022  | Learnt how to use reference links in Markdown | [reference links] |
| 13-02-2022  | Learnt media queries have many usecases | [usecases of media queries] |
| 14-02-2022  | Learnt why we should use logical properties | [why logical properties ?] | 
| 08-03-2022  | Learnt why this error occurs on strapi | [solution] |
| 09-03-2022  | Learnt how to change media type on strapi | ![modify media type on strapi] |
| 11-04-2022  | Learnt the difference between align-items and align-contents when using `display:flex;` | [flexbox align-content] |
| 11-04-2022  | Learnt about deconstructed pancake layout | [deconstruted pancake layout] |
| 29-04-2022  | Learnt how to fix env: node: No such file or directory on macOS | [solution] |
| 19-05-2022  | By default all flex items shrink since the default value of is `flex: 0 1 auto` | |
| 20-05-2022  | Learnt that align-items would work if height is set on the flex container irrespective of the flex-direction | [gif] |
| 21-05-2022  | Learnt setting fixed height on flex-items will tend to match with the sibilings flex-items and will stretch the content | |
| 22-05-2022  | Pro-tip: Try not to use `display:flex;` on mobile breakpoint and `display:flex;` on tablet or desktop breakpoint | |
| 16-06-2024  | Learnt how to access service exposed on K8s cluster locally | [port-forwarding] | |
| 05-07-2024  | Command for executing sonar-scanner for a nodejs project using jenkins scripted pipeline | [sonar-scanner-command] | |
| 01-01-2025  | Steps to setup docker CLI with non-root user privilages | [running docker as non-root user] | |
| 01-03-2025  | Learnt an interesting command to cleanup the container once it is exited | [clean up container after exit] |
| 02-03-2025  | git command to clone only a particular branch | [command for cloning a specific branch on git] |
| 05-03-2025  | Learnt that docker compose down does not remove the external volumes created we need to pass -v flag for removing the volumes also | [docker compose down]
| 06-03-2025  | Finally learnt on GNU/Linux systems `ctrl+l` I was trying to hit `cmd+k` from muscle memory of using a macOS | [clear terminal]
| 07-03-2025  | Came to know about Perfect Forward secercy security best practice | [Perfect Forward Secercy] |
| 09-03-2025  | Learnt about sar - system activity report command | [sar command] | 
| 11-03-2025  | Learnt that google spanner almost breaks the CAP theorem | [spanner CAP Theorem]
| 12-03-2025  | Turning on/off wifi via terminal | [nmcli] |
| 22-03-2025  | Today I learnt about a service name apprunner on AWS which is similar to GCP Cloud Run | [app runner]

