如果你的系统主要为Python服务，可以修改/home/judge/etc/judge.conf 设定 OJ_PYTHON_FREE=1 为了增加安全性，请在/home/judge/src/install目录运行sudo bash docker.sh，然后修改/home/judge/etc/judge.conf 设定 OJ_USE_DOCKER=1 这样设定后，可以提高Python的判题速度，并提供额外的安全防护。 推荐使用Ubuntu20.04作为基础系统，这个针对Python优化的方案在其他发行版未经测试。

시스템이 주로 Python을 제공하는 경우 /home/judge/etc/judge.conf를 수정하여 OJ_PYTHON_FREE=1로 설정할 수 있습니다. 보안을 추가하려면 /home/judge/src/install 디렉토리에서 sudo bash docker.sh를 실행한 다음 / home/judge/etc/judge.conf 설정 OJ_USE_DOCKER=1 이 설정 후에는 Python의 판단 속도를 향상시키고 추가 보안 보호를 제공할 수 있습니다. Ubuntu20.04를 기본 시스템으로 사용하는 것이 좋습니다. Python에 최적화된 이 솔루션은 다른 배포판에서 테스트되지 않았습니다.
