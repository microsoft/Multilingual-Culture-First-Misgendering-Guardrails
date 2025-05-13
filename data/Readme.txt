guardrails: contains language-specific guardrails

scenarios: contains scenario descriptions used to seed synthetic meeting transcript data creation

gold_transcripts: contains gold meeting transcripts containing edits by human annotators after the creation of synthetic data using the iterative pipeline

human_evaluation: contains evaluations done by the human annotators on base summaries and summaries with guardrails
 
LLM_judge_evaluation: contains evaluations done by the LLM judge on base summaries and summaries with guardrails

summaries_base: contains meeting transcript summaries without the use of language-specific guardrails

summaries_guardrails: contains meeting transcript summaries with the language-specific guardrails appended in the summarization prompt