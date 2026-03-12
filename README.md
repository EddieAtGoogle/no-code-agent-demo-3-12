# 🌟 ASCO Gemini Enterprise Workshop: No-Code Agent Lab

Welcome to the hands-on lab for **The Right Tool for the Right Goal** workshop!

In this activity, you will step into the shoes of an ASCO Community Advocate. Without writing a single line of code, you are going to build a **Mentorship Matchmaker & Career Coach**—a custom AI agent designed to help early-career oncologists navigate the ASCO Annual Meeting, find the right mentors, and confidently network.

Let's turn a blank chat window into a personalized career coach! 🚀

## 📁 What's in this repository?

You will need the two files provided in this repository to build your agent:

1. 📄 `ASCO 2026 Annual Meeting Agenda.txt`: This is our "Golden Path" mock dataset. It contains a text-based version of 50 realistic sessions from the upcoming Annual Meeting. By using a `.txt` file instead of a spreadsheet, we ensure the agent processes the information at lightning speed.

2. 📄 `no-code-agent-prompt.txt`: This contains the "System Instructions"—the strict, multi-step directions we will give the agent so it behaves like a structured coach rather than a basic search bar.

## 🛠️ Step-by-Step Instructions

### 📥 Step 1: Download the Lab Files

Before we begin, save the required files to your computer.

1. Click on `ASCO 2026 Annual Meeting Agenda.txt` above.

2. Click the **Download** button (the downward-pointing arrow icon near the top right of the file view) to save it to your desktop.

3. Do the same for `no-code-agent-prompt.txt`, or simply keep this page open so you can copy and paste the text later.

### 🚀 Step 2: Launch the Agent Designer

1. Open your **Gemini Enterprise** environment in a new browser tab.

2. Look at the left-hand navigation menu. Under the **Agents** section, click on **+ New agent**.

3. You are now on the **Agent Designer** welcome screen! You will see a conversational prompt bar at the bottom and an option to build manually.

### ⚙️ Step 3: Configure Your Agent

Because we want to give our agent strict rules and attach a specific document, we are going to use the manual builder.

1. On the Agent Designer screen, click the **Proceed to Builder** link located just above the chat bar on the right side.

2. **Name your Agent:** At the top of the screen, give your agent a title (e.g., *ASCO Mentorship Matchmaker*).

3. **Add the Instructions:** Open the `no-code-agent-prompt.txt` file you downloaded (or copy the text directly from GitHub). Paste that entire block of text into the **Instructions** or **System Prompt** box.

4. **Connect the Knowledge:** Look for the **Knowledge** or **Files** attachment section (often indicated by a paperclip icon `📎` or an "Upload" button). Upload the `ASCO 2026 Annual Meeting Agenda.txt` file from your computer.

### 🧪 Step 4: Test Your Agent!

Your agent is now fully built, grounded in ASCO data, and ready to coach! Let's test it out.

In the preview chat window on the right side of your screen, copy and paste the following prompt as if you were an ASCO member:

> *"I am a first-year fellow. I'm really interested in pediatric oncology and I'm trying to figure out how to manage long-term toxicities in my patients."*

Press **Enter** and watch the magic happen! ✨

## 🎯 What just happened?

Notice what your new agent accomplished in seconds:

* **Filtered the Noise:** It ignored 49 irrelevant sessions and zeroed in on the exact right pediatric oncology session.

* **Targeted a Mentor:** It identified the specific speaker as your ideal target.

* **Provided a Strategy:** It didn't just give you a schedule link; it gave you specific, highly intelligent clinical questions to ask at the microphone.

* **Drafted the Outreach:** It wrote a professional follow-up email ready to be sent.

**Congratulations!** You just built a high-value, governed AI product for the oncology community.
