## Five-step formula for creating efficient and effective training prompts for any type of task

1. Define the problem you are trying to solve and bucket it into one of the possible natural language tasks classification, Q & A, text generation, creative writing, etc.
2. Ask yourself if there is a way to get a solution with zero-shot (i.e. without priming the GPT-3 model with any external training examples)
3. If you think that you need external examples to prime the model for your use case, go back to step-2 and think really hard.
4. Now think of how you might encounter the problem in a textual fashion given the "text-in, text-out" interface of GPT-3. Think about all the possible scenarios to represent your problem in textual form.
5. If you end up using the external examples, use as few as possible and try to include variety in your examples without essentially overfitting the model or skewing the predictions.