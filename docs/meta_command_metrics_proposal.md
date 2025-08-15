# Meta-Command Metrics Proposal

## Proposed Metrics for Evaluating Meta-Commands

### Efficiency
- **Definition:** Measures the reduction in user input or repetitive instructions.
- **How to Measure:** Compare number of prompt tokens or steps required with and without meta-commands.

### Accuracy
- **Definition:** Assesses whether AI completes tasks correctly according to the meta-command.
- **How to Measure:** Evaluate output against expected results or ground truth.

### Consistency
- **Definition:** Determines if AI responds in a reliable manner across repeated uses of the same meta-command.
- **How to Measure:** Re-run commands multiple times and check for uniformity in output.

### User Satisfaction
- **Definition:** Captures subjective user experience with meta-commands.
- **How to Measure:** Surveys, ratings, or qualitative feedback from users.

### Naturalness
- **Definition:** Evaluates how natural the AI interaction feels when using meta-commands.
- **How to Measure:** User surveys or comparative studies with standard prompts; especially relevant for commands like `Sora` that influence grammatical form, TTS, and interaction style.

## Suggested Placement in Repository
- Directory: `docs/`
- File name: `meta_command_metrics_proposal.md`
- Rationale: Keeps all concept and methodology documentation centralized, separate from examples and tests, making it easy to reference during research and evaluation.

