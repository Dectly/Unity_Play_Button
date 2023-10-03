# Unity_Play_Button
Unity Play Button Tutorial. For any help join my discord https://discord.gg/8SYdJn5UpS

```cs
using System.Collections;
using System.Collections.Generic;
using UnityEngine;
using UnityEngine.SceneManagement;

public class SwitchScene : MonoBehaviour
{

    public void switchScenes(string sceneName)
    {
        SceneManager.LoadScene(sceneName);
    }

}
```
