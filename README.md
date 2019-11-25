# Unity2D_Text101
Unity 2D Projects (Text Objects)

using System.Collections;
using System.Collections.Generic;
using UnityEngine;
using UnityEngine.UI;

public class TextBehaviour : MonoBehaviour
{
    [SerializeField] Text textComponent;

    // Start is called before the first frame update
    void Start()
    {
        textComponent.text = "The game has started";
    }

    // Update is called once per frame
    void Update()
    {
        
    }
}
