# VEsNA Toolkit

Welcome to the VEsNA Toolkit organization! Here you will find an ecosystem of software tool compliant with the Virtual Environments via Natural language Agents (VEsNA) vision.  
We believe that, in the Generative AI and metaverse era, agent's sociality should involve humans by design, and situatedness should take virtual reality into account. Hence, our vision of the next generation intelligent software agents involves cognition and reasoning abilities, natural language interaction, and virtual reality.  
To make our vision concrete, starting from 2022 we designed and developed VEsNA, an open source project freely available to the research community that seamlessly integrates cognition (via Jason/JaCaMo), natural language (via intention based chatbots and LLMs), and virtual reality (Unity, in the VEsNA release developed in 2022; Godot in the version you find here). 

On the communication side, starting from the lower communication level, the [VEsNA Network kit](https://github.com/VEsNA-ToolKit/network-kit) provides different communication channels for artifacts and agents. In particular, you will find WebSocket communication and HTTP communication already implemented there. The VEsNA Network kit is used by VEsNA-light to connect the Jason minds of agents with their Godot bodies. Since the WebSocketand HTTP connections may turn out to be useful for other purposes, we decided to offer them as a stand-alone toolkit inside the ecosystem.

With [ChatBDI](https://github.com/VEsNA-ToolKit/chatbdi) you can insert the user inside your JaCaMo/Jason multi-agent system, allowing her to intract with JaCaMo agents via natural language. The current verions of ChatBDI exploits LLMs ([CodeGemma](https://ollama.com/library/codegemma), in particular) as the means to interact with agents in natural language. However, in previous releases, we integrated intention based chatbots ([Rasa](https://rasa.com/) and [Dialogflow](https://dialogflow.cloud.google.com)) in VEsNA. We are working to make them available again, as an alternative to LLMs. 

Moving to the implementation of the environment via virtual reality, 
[VEsNA-light](https://github.com/VEsNA-ToolKit/vesna-light) enables JaCaMo agents to be embodied inside a virtual environment currently implemented in Godot. This repository contains the bridge between [Jason](https://jason-lang.github.io/)/[JaCaMo](https://jacamo-lang.github.io/) agent minds and [Godot](https://godotengine.org/) agent bodies. As for ChatBDI, whose current implementation supports LLM but that is undergoing the integration of other chatbot interfaces, also the virtual reality environment is not meant to be limited to Godot. The integration of [Unity](https://unity.com/), where we started from, is indeed under way.

[KQML-S](https://github.com/VEsNA-ToolKit/KQML-S) is an extension of the KQML agent communication language to consider situatedness implemented inside the VEsNA framework. It represents a bridge between the agent's situatedness and its social ability. 


## Try VEsNA and contact us for any question!

[Andrea Gatti](mailto:andrea.gatti@edu.unige.it), [Angelo Ferrando](mailto:angelo.ferrando@unimore.it), [Viviana Mascardi](mailto:viviana.mascardi@unige.it)
