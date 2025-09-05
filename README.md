
---

# EXPERIMENT – 3: Scenario-Based Report Development with Diverse Prompting Methods

### Register No.: 212223060075

### Date: 05.09.2025

---

## Aim:

To create an intelligent chatbot capable of assisting users with product troubleshooting, delivery updates, and frequently asked questions. The chatbot should demonstrate efficiency, accuracy, and a natural style of conversation. Different prompting techniques such as **Straightforward Prompting, Tabular Prompting, and Preceding Question Prompting** are applied to analyze their effectiveness.

---

## Tools Required:

* AI text generation system (ChatGPT, Gemini, Claude)
* MS Word/Excel (for documenting outputs)
* Internet access for live interaction testing

---

## Theory:

Prompt engineering refers to designing and structuring inputs given to AI systems to achieve accurate and user-relevant outputs. Different prompting strategies affect the **clarity, depth, and format** of chatbot responses.

1. **Straightforward Prompting**

   * Simple and direct instruction.
   * Produces focused answers for short queries.

2. **Tabular Prompting**

   * AI is explicitly asked to present output in table form.
   * Best for structured data, comparisons, or multi-step solutions.

3. **Preceding Question Prompting**

   * Builds context from previous user questions.
   * Enables a continuous, interactive flow of conversation.

---

## Procedure:

Three scenarios were tested with all three prompting types. The responses were analyzed based on **clarity, structure, and engagement**.

---

### Scenario 1: Product Troubleshooting

| **Prompt Type**              | **Example Prompt**                                                         | **Sample Output**                                      |
| ---------------------------- | -------------------------------------------------------------------------- | ------------------------------------------------------ |
| Straightforward Prompting    | “My washing machine is not draining water. What should I do?”              | *Check drain pipe, remove blockages, restart machine.* |
| Tabular Prompting            | “List causes and fixes for a washing machine not draining water.”          | See table below.                                       |
| Preceding Question Prompting | Q1: “My washing machine won’t drain.” <br> Q2: “It makes a humming sound.” | *Motor issue suspected; service required.*             |

**Troubleshooting Table Output:**

| **Possible Cause** | **Solution**                   |
| ------------------ | ------------------------------ |
| Blocked drain pipe | Clean or unclog pipe.          |
| Faulty pump        | Replace or repair pump.        |
| Overloaded clothes | Reduce load and restart cycle. |
| Motor issue        | Contact service technician.    |

---

### Scenario 2: Order Tracking

| **Prompt Type**              | **Example Prompt**                                     | **Sample Output**                            |
| ---------------------------- | ------------------------------------------------------ | -------------------------------------------- |
| Straightforward Prompting    | “Track order #88954 placed on 30th August.”            | *Shipped, arriving 6th September.*           |
| Tabular Prompting            | “Show current status of order #88954 in table format.” | See table below.                             |
| Preceding Question Prompting | Q1: “Where is order #88954?” <br> Q2: “Is it delayed?” | *Expected to arrive on time, 6th September.* |

**Order Status Table:**

| **Stage**       | **Status**         | **Date**    |
| --------------- | ------------------ | ----------- |
| Order Confirmed | Successful         | 30-Aug-2025 |
| Packed          | Completed          | 31-Aug-2025 |
| Shipped         | In transit         | 02-Sep-2025 |
| Delivery        | Expected 06-Sep-25 | —           |

---

### Scenario 3: General Inquiry

| **Prompt Type**              | **Example Prompt**                                                              | **Sample Output**                                                |
| ---------------------------- | ------------------------------------------------------------------------------- | ---------------------------------------------------------------- |
| Straightforward Prompting    | “What is your company’s return policy?”                                         | *Return within 15 days of delivery.*                             |
| Tabular Prompting            | “Show return and replacement policy details in a table.”                        | See table below.                                                 |
| Preceding Question Prompting | Q1: “Do you allow returns after 20 days?” <br> Q2: “Then what about exchanges?” | *No returns after 20 days, but exchanges allowed up to 30 days.* |

**Return/Replacement Policy Table:**

| **Policy Type** | **Details**                       |
| --------------- | --------------------------------- |
| Return          | Within 15 days of purchase.       |
| Replacement     | Allowed up to 30 days.            |
| Refund          | Processed within 7 business days. |

---

## Observations:

* Straightforward prompts were best for **direct answers** like policy details.
* Tabular prompts gave **clear and structured outputs**, suitable for troubleshooting and comparisons.
* Preceding question prompts allowed the chatbot to **carry forward context** and improve conversation flow.

---

## Conclusion:

By applying the three prompting techniques, the chatbot effectively handled multiple customer queries. Each technique served a distinct role:

* **Straightforward Prompting** → Quick, factual answers.
* **Tabular Prompting** → Organized and detailed responses.
* **Preceding Question Prompting** → Contextual and conversational replies.

The combination of these methods makes the chatbot **efficient, reliable, and user-friendly**.

---

## Result:

The experiment was successfully executed. The chatbot responded effectively to troubleshooting, order tracking, and general inquiries using diverse prompting strategies.

---
