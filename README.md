# ProjectHavenWebGL
WebGL build host repository

WebGL build works after build, but directs to 404 error when using github-provided url
  - Added "&& Application.platform != RuntimePlatform.WebGLPlayer" condition to:
      "if(Application.isBatchMode)
      {
            dedicatedButton.onClick.Invoke();
      }
      to prevent dedicated mode on webgl instance
  - Disable webgl socket on lobbymanager
