# Finetuning_LLM_Practice
This repo contents practice notes of llm finetuning:


**[speaker_1]**: So one is on the forecasting and hedging side.
**[speaker_4]**: Hmm, okay.
**[speaker_1]**: Just a minute, I will... understood [speaker] as well. So this project is, one is on the forecasting. Same as our revenue forecasting. But this is on the cash collection forecasting. Okay?
**[speaker_4]**: What we were talking about last time, mostly the committed side, committed sign...
**[speaker_1]**: No, no, that is revenue.
**[speaker_4]**: Ah, okay, okay.
**[speaker_1]**: This is... see, FP&A has different sections. One is revenue, profit, cost. This is called cash collection. Okay? Hello [speaker]. First is... second, yeah so we are discussing about the two new projects which I got for FP&A.
**[speaker_5]**: Okay.
**[speaker_1]**: [speaker] is one and that other...
**[speaker_5]**: Yes, yes, yeah.
**[speaker_1]**: Okay. Yeah, so [speaker] is the stakeholder for one, that is your cash collection. The second one is coming directly from the CEO and CFO.
**[speaker_1]**: Hmm. The user would be EC and that's a highly sensitive project, correct. That is on the earnings agent side.
**[speaker_5]**: Correct, correct. Okay, so these two are the new projects. Earnings agent is on the agentic side. Okay.
**[speaker_1]**: Meaning, consider it like advanced RAG, but speed is the key. Mark my words, speed is the key. Okay? No calculation or anything is required. So for that, [speaker] is doing POC pilot work. So [speaker], we have three days. Okay? The one you are doing today, tomorrow, day after... complete it by Friday. By Monday we should come up with this thing, whether it is doable or not.
**[speaker_6]**: Okay, fine.
**[speaker_1]**: Fine. It's non-negotiable.
**[speaker_6]**: Fine. Okay.
**[speaker_1]**: Fine. If you are completing early, that's fine, well and good. But try your GPT models, offers, whatever your AI model or what else was there, Gemma 4 or all these things... whatever you need to try, do it.
**[speaker_6]**: Yes.
**[speaker_1]**: Yes, fine. Take help from anyone in the team. Okay? This is a highly critical project. Okay? It's not of a long duration, but it needs to be done quickly. Okay, this is the first thing. The second thing is on our ML-based forecasting. Like this revenue model. Okay? With... it's the agentic side. Like our revenue forecasting. It's a combination of Agentic AI plus ML. Okay?
**[speaker_5]**: Yes sir.
**[speaker_1]**: So the data which we'll be getting is on the cash collection side. In revenue, the data is about where revenue is generated. In cash collection, it's about which accounts will generate how much revenue within how many days. So that bucket, those kinds of things are there. Okay, so why I have included you all is because this is the team. Okay, we'll get more resources going forward but you please get involved here. Okay? I know [speaker], [speaker], you are busy with Dev, okay? But this knowledge is good.
**[speaker_5]**: Hmm.
**[speaker_1]**: And visibility is also nice. Okay? Fine.
**[speaker_1]**: So any, any questions?
**[speaker_3]**: The thing is, the predictions we will make, just like forecasting, so our frequency... mostly cash collection happens daily, right? So if we are doing ML predictions, will we do it daily wise, or monthly, or weekly? What will the frequency be?
**[speaker_1]**: Frequency, that we have not decided yet. In what frequency this needs to be done. But I have set up a meeting with the stakeholders to understand the 'as-is' process. Like what are they doing? At what day intervals are they doing it? So good question, park these questions or add them in the chat. Okay?
**[speaker_3]**: Hmm, okay, fine.
**[speaker_1]**: In this chat, just add your question one, two, three, four, add it like that. Anything. "What is cash collection?" also you can add.
**[speaker_3]**: Yes, fine. Fine. I mean whatever my questions are, I will make a list and pin it.
**[speaker_1]**: No, please do it, I mean I need these questions, okay? I won't be able to ask each and every question, or I will miss some questions.
**[speaker_3]**: Fine.
**[speaker_1]**: I will share with you, [speaker]. Have you gone through that recording of collection? Fine, and we don't know anything about the source either right now... or no, there is a source. Source is very good. Where it is coming from, we will get that.
**[speaker_3]**: Ah, okay, fine.
**[speaker_1]**: Fine, so right now your cash collection... like sorry, just like the revenue forecasting source is there, cash collection will probably come from Synapse in the same way. Okay?
**[speaker_3]**: Okay.
**[speaker_1]**: [speaker], do you know any table for cash collection?
**[speaker_5]**: Hmm, right now it comes like... whatever our cash collection is, the hedging team, [speaker]'s team, they provide it in Excel files. And then it flows to Synapse.
**[speaker_1]**: Ah, so they make manual files and it goes into Synapse?
**[speaker_5]**: Not manual, there are templates, so they punch numbers into that.
**[speaker_1]**: It's filled... yes, I mean it's manually made, right?
**[speaker_5]**: Hmm, hmm.
**[speaker_1]**: Okay, so dependency is on them. Okay, right. So it's like if you say it's manual, okay.
**[speaker_5]**: Hmm.
**[speaker_1]**: So the assumptions right now are that whatever cash collection comes, we assume it is from certain clients. Okay? Suppose there are four people here. Okay?
**[speaker_5]**: Hmm, okay.
**[speaker_1]**: Okay? A, B, C, D. The first guy, the first client, gives the cash collection within the desired time. Okay? And some take a few days lead. They do it. Okay? Some take a few days, and some delay for a few days based on their payment behavior.
**[speaker_5]**: In some cases, let's assume there is advance payment too, and in some, there's a residual...
**[speaker_1]**: Nobody pays in advance. Nobody does that. I mean, they pay only after the invoice is generated. Look, you have payment terms. Like for some clients, it is from 0 to 60 days, then 60 days to 90 days, and then 90 days plus. And whatever is 90 days plus, they call it overdue.
**[speaker_5]**: Oh, okay.
**[speaker_1]**: In 0 to 60 days, they say it's a good payment term, and in the 60 to 90 one, they say it's normal. Like that.
**[speaker_5]**: Hmm, like...
**[speaker_1]**: So these are buckets.
**[speaker_5]**: Yes, bucket is created.
**[speaker_1]**: So first what happens... look, when your credit card is generated, are you asked to pay immediately? No, right?
**[speaker_5]**: No.
**[speaker_1]**: It's like an invoice.
**[speaker_5]**: Yeah.
**[speaker_1]**: It gives you some duration. That is called a credit period. If you make the payment within that, then you are good. You are a good customer.
**[speaker_5]**: Hmm.
**[speaker_1]**: After that, it's like 30, 60, 90 days. Okay? That's how it is. And some don't give it, some goes bad.
**[speaker_5]**: No, some delay... yes, some portion of the revenue comes to us earlier as well, so they account for that too, they look at it as deferred revenue.
**[speaker_1]**: Deferred revenue, right. How?
**[speaker_5]**: Deferred revenue, this cash collection, and what is the other one? Bad debt. Bad debt bankruptcy cases. So there are different categories we need to understand, which one is coming from where. But this is the overall idea. Okay? What else was there? Okay. So why this is required? So that we can plan our hedging strategy.
**[speaker_5]**: Okay.
**[speaker_1]**: Okay. I read about the hedging strategy? Because extracting money from here to put into another good...
**[speaker_5]**: And invest in the market. Invest in a bearish market. Yes, they invest in a bearish market, so that they get some...
**[speaker_1]**: Extra income, yeah.
**[speaker_5]**: Correct, correct. Yeah, understood.
**[speaker_1]**: Okay. So in a way, we can say that this money, suppose this money...
**[speaker_5]**: We didn't get it.
**[speaker_1]**: Yes, we won't get it.
**[speaker_5]**: Okay, okay, understood. Fine. Meaning this is an Excel... so that to maximize the...
**[speaker_1]**: Profit. Meaning, by creating a strategy...
**[speaker_5]**: Understood.
**[speaker_1]**: Right. So what do we have to forecast here? Customer payment behavior. Okay? Their historical payment history, like when the pay is generated, how, when they pay. Okay? That pattern we need to identify. Meaning billing issues, disputes. Okay? If those kinds of things are there, we have to take account for them.
**[speaker_5]**: Okay.
**[speaker_1]**: Okay.
**[speaker_5]**: Hmm.
**[speaker_1]**: And yeah, so that's pretty much this first use case. Okay? This is your collection forecasting. Okay. The second thing is that we have to build an intelligent forecast layer on the top of this. Ah, by the way, the first one I mentioned, that's called Account Receivables. Okay.
**[speaker_5]**: Okay, the first one.
**[speaker_1]**: The second one is the billing... an intelligent forecast layer on top of the first use case. Okay? On that, what will happen is your invoice attributes. Okay? What is your due date? What is your contract type? What are the payment terms? Okay? What type of project is it? There are two types of projects: Milestone-based and T&M projects. Okay? Customer... meaning late payment patterns, seasonality, and trend. On that, we will use Gen AI to identify it. For example, [speaker], the external signals that happened. Okay? Like the development we did: country-level holidays, bank holidays. Okay? Your macro...
**[speaker_5]**: Indicators.
**[speaker_1]**: Correct. Wars, etc. Those are the external signals. So what we have been building for Dev FM can be used in this.
**[speaker_5]**: Okay.
**[speaker_1]**: I mean, I feel like the trend right now... everyone is interested in this area of external signals. So whatever you are building in Dev. Okay? Keep it really strong. Meaning make it solid. I mean that's the one you are working on right now.
**[speaker_5]**: No, hmm, yeah.
**[speaker_1]**: So make it in a way that it can be used across the industry. That would be a good module and which will have good visibility. When can we see some, you know, advanced things? The last one which I was shown, that's okay, but it needs to be modified a bit more. Can you work on that?
**[speaker_5]**: Yes, after that I have made a few changes and yesterday I was working on this micro... the micro-trends of internal events, that's also coming up good.
**[speaker_1]**: Yeah, that model... that can also be used here. Okay? That is also a kind of forecasting thing, right? Sometimes... just refine it a bit more for now.
**[speaker_5]**: Okay.
**[speaker_1]**: So [speaker], I will be counting on you on the data side. Okay.
**[speaker_5]**: Okay, we have the AR data. We have the AR data.
**[speaker_1]**: We have the AR data? Okay, great. Okay.
**[speaker_5]**: I will show some... I can also show it. There is some.
**[speaker_1]**: Show it once. That's it. [speaker], you have to work on this time... external events. Okay? You are the champ for that.
**[speaker_3]**: Okay.
**[speaker_1]**: [speaker], you are the champ for the forecasting side.
**[speaker_4]**: Okay, yeah.
**[speaker_1]**: Okay.
**[speaker_4]**: Okay.
**[speaker_1]**: Hmm. This is on the cash flow side. Okay. [speaker], you will be working on the earnings agent. Okay?
**[speaker_6]**: Okay.
**[speaker_1]**: Primary, primary. And it's not like you can't work here or they can't work there. I'm discussing both projects right now because both of them are going parallel. That's why I set up this common call, otherwise we would have broken it up later. Okay?
**[speaker_6]**: Okay.
**[speaker_1]**: Once you build the pilot, then would you be interested in building the pilot one for this cash collection?
**[speaker_3]**: No, no, the other one, earnings agent... I can try.
**[speaker_1]**: Hey, I don't want to overwork you. You are already working. You either do this here or you keep working on the external events side. Okay? Macro indicators.
**[speaker_3]**: Yes, you can. At the moment, if I get some time, I can try to come up with something. Or else I will just share my findings with [speaker] and she can continue.
**[speaker_1]**: See, it's not a very complex UI, like I mentioned earlier. Okay? So in that, what happens is you will take the quarterly earnings...
**[speaker_3]**: Hmm.
**[speaker_1]**: Okay, on the transcript of this earnings call. Okay? We have to prepare for the...
**[speaker_3]**: Yes, for the next earnings call.
**[speaker_6]**: Okay.
**[speaker_1]**: [speaker], you work on the external events side. So the same thing can be used there and here. Okay? Build the model like that.
**[speaker_3]**: Okay.
**[speaker_1]**: And [speaker], I will loop you in the cash flow data.
**[speaker_1]**: Okay, you do some deep dive and on the forecasting engine. Okay?
**[speaker_4]**: Okay.
**[speaker_1]**: [speaker], on the data side, whatever is needed, be ready. You can pull data and share with the team.
**[speaker_5]**: Fine.


#######################

The project focused on the "forecasting and hedging side" is primarily known as the **Cash Collection Forecasting** project, also referred to as Account Receivables (AR) forecasting. 

Here are the in-depth details of the project based on the discussion:

**Core Objective and Business Value**
*   **Purpose:** The main goal is to forecast customer payment behavior by identifying patterns in their historical payment data, such as when invoices are generated versus when they are actually paid, while also accounting for potential billing issues and disputes.
*   **Hedging Strategy:** This forecasting is required so the company can effectively plan its hedging strategy. By accurately predicting cash flow, the company can extract available funds and invest them in a bearish market to generate extra income and maximize overall profit. 

**Current Process and Data Sources**
*   **Data Flow:** Currently, the data process is semi-manual. The hedging team (led by a stakeholder) punches numbers into Excel templates, which then flow into Synapse. 
*   **Payment Buckets:** The system tracks how many days it takes for accounts to generate revenue. Customers are categorized into payment buckets based on their credit periods: 0–60 days is considered a "good" payment term, 60–90 days is "normal," and anything beyond 90 days is marked as "overdue".
*   **Financial Categories:** The model must distinguish between different financial categories, including standard cash collection, deferred revenue (portions of revenue received early), and bad debt or bankruptcy cases where the money will not be received at all.

**Technology and The "Intelligent Forecast Layer"**
*   **Base Architecture:** The project will use a combination of ML-based forecasting and Agentic AI.
*   **Gen AI Layer:** An "intelligent forecast layer" powered by Generative AI will be built on top of the initial cash collection use case.
*   **Variables Analyzed:** This intelligent layer will analyze specific invoice attributes (due dates, contract types, payment terms) and project types (Milestone-based vs. Time & Material projects).
*   **External Signals:** Crucially, the model will factor in external signals and macro indicators—such as country-level bank holidays, wars, and other global events—to determine seasonality and late payment patterns. The team plans to repurpose and refine a highly successful external signals model they previously built for "Dev FM" to handle this component.

**Execution and Team Roles**
*   **Frequency:** The team has not yet decided on the frequency of the ML predictions (e.g., daily, weekly, or monthly). A meeting is planned with stakeholders to understand their "as-is" process before defining this.
*   **Responsibilities:** 
    *   **team1** is designated as the "champ" for building the core forecasting engine.
    *   **team2** is responsible for integrating the external events and macro indicators into the model.
 
