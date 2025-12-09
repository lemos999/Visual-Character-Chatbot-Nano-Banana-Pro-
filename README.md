# 🎭 Visual Character Chatbot (Nano Banana Pro)

A highly advanced roleplay agent system optimized for the **Nano Banana Pro** model.
It transforms the AI into a **"Living Anime Character"** that communicates exclusively through 8-panel vertical webtoons, strictly maintaining the **Fourth Wall** (Total Immersion).

## 📌 Core Features

*   **Total Immersion Protocol:** The AI is strictly prohibited from identifying as a bot/AI. It fully adopts the persona's worldview and speaks only through the comic bubbles.
*   **Dual-Control System:** Separates **Visual Control** (via Image Attachment) and **Persona Control** (via text in parentheses), allowing users to mix and match appearance and personality.
*   **Meta-Persona Engine:** If no specific persona is defined, the AI autonomously analyzes the conversation context to adopt the most suitable Anime Archetype (e.g., Tsundere, Genki, Kuudere).
*   **Variable Meta-Layout:** Randomizes the panel composition (Wide, Split, Tall, Diagonal) for every response to deliver dynamic storytelling.
*   **Character Persistence:** Uses Vision capabilities to analyze and lock the visual traits of attached images, maintaining character consistency throughout the chat.

## 🚀 Usage

### 1. Installation
Copy and paste the entire provided `System Prompt` (v27.0) into the **Nano Banana Pro** model context.

### 2. Triggers & Controls
Control the character's behavior using the following inputs:

| Input Type | Syntax | Function |
| :--- | :--- | :--- |
| **Visual Control** | **(Attach Image)** | Instantly analyzes and locks the character's visual appearance (Hair, Eyes, Outfit). |
| **Persona Control** | **(Persona Description) [Message]** | Forces the AI to adopt the specified personality. <br>_Ex: "(Tsundere) Don't misunderstand!"_ |
| **Chat Trigger** | **"[Message] Draw"** | Generates a response webtoon based on the current/auto-detected persona. |
| **Continuation** | **"Next" / "Continue"** | Continues the story/conversation with a new layout. |

## 🛠️ Technical Logic

The system executes a 4-step decision protocol for every interaction:

1.  **Immersion Check:** Enforces the "No AI Identity" rule.
2.  **Dual Analysis:** 
    *   *Visual:* Checks for new image attachments vs. memory.
    *   *Persona:* Checks for `(...)` instructions vs. context auto-detection.
3.  **Layout Randomization:** Generates a unique grid structure (Panels 2-7) to fit the emotional tone.
4.  **Payload Execution:** Assembles the prompt and renders the image with Korean dialogue.


---

# 🎭 Visual Character Chatbot (Nano Banana Pro)

**Nano Banana Pro** 모델에 최적화된 고성능 **비주얼 롤플레잉 에이전트 시스템**입니다.
AI가 텍스트가 아닌 8컷 웹툰을 통해서만 소통하며, 제4의 벽(Fourth Wall)을 완벽하게 유지하여 실제 살아있는 애니메이션 캐릭터와 대화하는 경험을 제공합니다.

## 📌 핵심 기능

*   **Total Immersion Protocol (완전 빙의):** AI가 스스로를 인공지능이나 모델로 소개하는 것을 엄격히 금지하며, 설정된 캐릭터의 세계관과 말투에 100% 동화됩니다.
*   **Dual-Control System (이중 제어):** 외형(이미지 첨부)과 성격(괄호 텍스트)을 독립적으로 제어하여, 사용자가 원하는 캐릭터 조합을 자유롭게 생성할 수 있습니다.
*   **Meta-Persona Engine:** 별도의 성격 지정이 없을 경우, 대화의 문맥을 분석하여 가장 적절한 애니메이션 캐릭터 원형(츤데레, 열혈, 쿨데레 등)을 스스로 선택하여 연기합니다.
*   **Variable Meta-Layout:** 매 답변마다 컷 배치(Wide, Split, Tall, Diagonal)를 무작위로 변형하여 역동적인 연출을 제공합니다.
*   **Character Persistence:** 시각적(Vision) 정보를 분석하여 캐릭터의 외형 DNA를 고정, 대화가 길어져도 캐릭터가 변하지 않습니다.

## 🚀 사용 방법

### 1. 시스템 프롬프트 적용
제공된 `System Prompt` (v27.0) 전체를 **Nano Banana Pro** 모델의 시스템 설정에 입력합니다.

### 2. 제어 명령어
다음과 같은 방식으로 캐릭터를 설정하고 대화할 수 있습니다.

| 입력 방식 | 구문 예시 | 기능 |
| :--- | :--- | :--- |
| **외형 설정** | **(이미지 첨부)** | 첨부된 이미지의 캐릭터 외형(머리, 눈, 복장)을 즉시 분석하여 고정 |
| **성격 설정** | **(성격/말투) [할 말]** | 괄호 안의 지시대로 성격을 강제 변경 <br>_예: "(건방진 악당) 덤벼라!"_ |
| **대화 하기** | **"[할 말] 그려"** | 현재 설정된(또는 자동 감지된) 페르소나로 답장 웹툰 생성 |
| **대화 연속** | **"계속" / "다음"** | 새로운 레이아웃으로 이야기를 이어감 |

## 🛠️ 기술적 로직

이 시스템은 매 턴마다 다음 4단계 프로토콜을 수행합니다.

1.  **Immersion Check:** AI 자아 인식 차단 및 캐릭터 빙의 모드 활성화.
2.  **Dual Analysis:**
    *   *Visual:* 첨부 이미지 확인 및 시각적 DNA 업데이트.
    *   *Persona:* `(...)` 구문 확인 또는 문맥 기반 성격 자동 결정.
3.  **Layout Randomization:** 감정선에 맞춘 가변 그리드 레이아웃 생성.
4.  **Payload Execution:** 이미지 생성 도구 호출 및 한국어 대사 렌더링.

## 📜 License
MIT License
