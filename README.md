# Smart Expense Tracker with Python & LLMs

Keeping track of daily expenses sounds simple, but in reality, receipts get lost and categories are forgotten. This project solves that problem by building a smart expense tracker that not only records transactions but also understands them using Large Language Models (LLMs).
Instead of manually assigning categories every time, the system can read expense notes like “Netflix Monthly Plan” or “Uber Ride” and automatically classify them into meaningful categories such as Food, Transportation, or Entertainment.

What This Project Does?
->Stores daily income and expense records

->Automatically categorizes expenses using an LLM

->Summarizes spending by category

->Visualizes spending patterns using charts

->Provides an interactive dashboard using Streamlit

The goal is not just to log data, but to make spending patterns easy to understand.

How It Works (High Level)?

->Expense data is stored and managed using Pandas

->Each expense note is analyzed by an LLM (OpenAI API)

->The model assigns the most relevant category automatically

->Spending is summarized and visualized with charts

A Streamlit dashboard displays everything in real time

Tech Stack:
Python
Pandas
Streamlit
OpenAI API (LLM-based categorization)
Matplotlib (visualizations)

Why This Project?
Traditional expense trackers require too much manual work.
This project demonstrates how LLMs can simplify everyday tasks by adding intelligence on top of simple data pipelines.

It is ideal for:
Learning Python + Streamlit
Understanding practical LLM integration
Academic mini-projects
Personal finance experiments

Future Improvements:
Monthly and yearly summaries in natural language
CSV / Excel export
Better category coverage
Budget alerts and insights
