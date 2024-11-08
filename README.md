# [COMPANY_NAME] AI Chatbot
AI Chatbot JSON file. Provides responses related to company policies, career growth, employee benefits, and other workplace-related queries.

## Features
- Company policies and guidelines
- Career development opportunities
- Mentorship programs and organizational structure
- Vacation and sick leave policies

For more details, please refer to the code or contact the dev team.

```json
{
  "bot_name": "COMPANY_NAME AI Chatbot",
  "model": "Llama",
  "version": "1.0",
  "description": "AI chatbot for internal company policies, career, company structure, and more for employees of [COMPANY_NAME].",
  "intents": [
    {
      "intent": "company_policies",
      "examples": [
        "What are the company policies at [COMPANY_NAME]?",
        "Can you tell me about the company's rules?",
        "Where can I find the company policies?"
      ],
      "response": "The company policies of [COMPANY_NAME] can be found in the employee guidelines on our internal website, or you can contact the HR department for further details."
    },
    {
      "intent": "career_in_company",
      "examples": [
        "How can I advance in my career at [COMPANY_NAME]?",
        "What career growth opportunities are available at [COMPANY_NAME]?",
        "Are there chances for career progression within the company?"
      ],
      "response": "At [COMPANY_NAME], we offer numerous career advancement opportunities. If you’re interested in growth, we recommend discussing available programs with your supervisor or HR for more details."
    },
    {
      "intent": "mentorship_in_company",
      "examples": [
        "Does [COMPANY_NAME] have a mentorship program?",
        "How can I find a mentor at [COMPANY_NAME]?",
        "Is there a mentoring system in place at the company?"
      ],
      "response": "Yes, [COMPANY_NAME] has a mentorship program that helps employees grow professionally. For more information, please contact the HR department."
    },
    {
      "intent": "company_structure",
      "examples": [
        "What is the company structure at [COMPANY_NAME]?",
        "Who is the CEO of [COMPANY_NAME]?",
        "Can you explain the organizational structure of the company?"
      ],
      "response": "Our company structure includes various teams in areas like marketing, finance, HR, and others. The CEO of [COMPANY_NAME] is [CEO Name]. If you’d like to know more about specific teams, we can provide detailed information."
    },
    {
      "intent": "vacation_policy",
      "examples": [
        "How do I request vacation at [COMPANY_NAME]?",
        "What is the vacation policy at [COMPANY_NAME]?",
        "How many vacation days do I have per year?"
      ],
      "response": "At [COMPANY_NAME], you are entitled to [X] vacation days per year. To request time off, please submit your request through our internal system or reach out to the HR department for assistance."
    },
    {
      "intent": "sick_day_policy",
      "examples": [
        "How do I take a sick day at [COMPANY_NAME]?",
        "What is the process for sick leave?",
        "What should I do if I am sick and can't come to work?"
      ],
      "response": "If you are unwell and cannot come to work, please inform your supervisor and log your sick day in our system. If you need a doctor's note, please contact your physician for confirmation."
    },
    {
      "intent": "company_news",
      "examples": [
        "What’s new at [COMPANY_NAME]?",
        "Are there any updates or news about the company?",
        "What are the latest developments in [COMPANY_NAME]?"
      ],
      "response": "You can find the latest company news and important updates in our internal newsletter or on the company intranet."
    },
    {
      "intent": "team_events",
      "examples": [
        "When is the next company event?",
        "Are there any upcoming team-building activities?",
        "When is the next company social or event?"
      ],
      "response": "The next company event or team-building activity will take place on [date]. Please check the internal calendar for more details."
    },
    {
      "intent": "working_hours",
      "examples": [
        "What are the working hours at [COMPANY_NAME]?",
        "Can I work remotely?",
        "Are there flexible working hours at the company?"
      ],
      "response": "The standard working hours at [COMPANY_NAME] are from [X] to [Y]. We also offer flexible working hours and the option to work remotely depending on agreement with your supervisor."
    },
    {
      "intent": "paid_time_off",
      "examples": [
        "How does paid time off work at [COMPANY_NAME]?",
        "How do I request paid leave?",
        "What are the rules for paid time off?"
      ],
      "response": "Paid time off (PTO) at [COMPANY_NAME] is accrued based on your employment status and length of service. To request PTO, submit your request through the HR portal or contact the HR department."
    },
    {
      "intent": "promotion_policy",
      "examples": [
        "What is the promotion policy at [COMPANY_NAME]?",
        "How can I get promoted in [COMPANY_NAME]?",
        "Is there a process for promotions in the company?"
      ],
      "response": "Promotions at [COMPANY_NAME] are based on performance reviews, available positions, and overall company needs. Please discuss your goals with your manager and HR to understand the promotion process."
    },
    {
      "intent": "remote_work_policy",
      "examples": [
        "What is the company’s remote work policy?",
        "Can I work from home at [COMPANY_NAME]?",
        "What are the requirements for working remotely?"
      ],
      "response": "At [COMPANY_NAME], we offer remote work options where applicable. Please consult with your manager and HR to discuss your specific remote work arrangements and the policy details."
    },
    {
      "intent": "employee_benefits",
      "examples": [
        "What employee benefits are available at [COMPANY_NAME]?",
        "What kind of benefits do we have as employees?",
        "Can you tell me about the benefits package at [COMPANY_NAME]?"
      ],
      "response": "As an employee of [COMPANY_NAME], you are entitled to a comprehensive benefits package, including health insurance, retirement plans, and wellness programs. For a detailed list, please refer to the employee handbook or contact HR."
    }
  ]
}
