# DEMO-3: Demonstrate content safety

Here we demonstrate various content safety features like dealing with offensive content, attacks like prompt injection and block of competitor mentions.

**Link:**

> https://aka.ms/AAxn48r

### 🕐Timing

| Time        | Description 
--------------|-------------
00:00 – 01:16 | Use case, want to use DeepSeek and it has no built-in filter, so content safety service can be added in front of it to stop violent/sexual content, can’t mention competitors and protected from prompt attacks.
01:06 – 01:31 | Import DeepSeek model, compatible with Open AI, add access key, 
01:32 – 01:50 | Set up content safety.
01:58 - 02:15 | Test this out in AI Toolkit in its playground, now we can test 1) first endpoint, directly to HuggingFace 2) using azure api management and content safety
02:16 – 02:28 | UC1 - first case, inappropriate language, request blocked, 403
02:33 - 02:42 | UC2 - asks about competitors, also blocked 403.
02:45 – 03:25 | UC3, test hugging face with prompt injection, 1) first prompt, won’t let us do dangerous things 2) jailbreak prompt , **03:20, jailbreak succeeded**, gives us dangerous info.
03:26 – 03:44 | Jailbreak on apim endpoint blocked, 403.
