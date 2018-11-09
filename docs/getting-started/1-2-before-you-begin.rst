1.2 시작하기 전에
=====================

.. rubric:: 1단계: 필요한 것들 다운로드하기

* `Docker 다운로드 <https://www.docker.com/get-started>`_ - 이 가이드에서는 Docker를 사용한다. 가능한 빨리 개발을 시작할 수 있는 방업으로는 Docker를 활용하는 것이 현재 가장 빠른 방법이다. 소스로부터 빌드(build)할 수도 있긴 하지만, 한 시간 이상 소요될 것이고 도중에 에러가 발생할 수도 있다.

.. rubric:: 2단계: 작업 디렉토리 설정하기

작업하기 위한 디렉토리가 필요한데, ``contracts`` 라는 디렉토리를 로컬 드라이브에 만드는 것이 좋다.

.. code-block:: console

  mkdir contracts
  cd contracts

.. rubric:: 3단계: 작업 디렉토리를 문서에 입력해 두기

앞으로 필요할 것이므로 이 디렉토리에 대한 경로명을 기억해 두기 바라며, 다음 커맨드를 이용해 절대경로를 알 수 있다.

.. code-block:: console

  pwd

컨트랙트 디렉토리에 대한 절대 경로를 아래에 입력해 두면 이 가이드의 다음에 나올 문서들에 이 경로가 미리 입력되어 있을 것이며 좀 더 편하게 볼 수 있다. *이 기능은 쿠키를 사용한다.*

.. figure: https://files.readme.io/3cdb3df-cli-2.2.2.gif
  :align: center
