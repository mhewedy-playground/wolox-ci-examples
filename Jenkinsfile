library identifier: 'wolox-ci@use-image-no-dockerfile', 
        retriever: modernSCM([$class: 'GitSCMSource', remote: 'https://github.com/mhewedy/wolox-ci.git'])

node {
  checkout scm
  woloxCi('.pipeline.yaml');
}

