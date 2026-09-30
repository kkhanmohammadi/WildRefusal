# WildRefusal

**WildRefusal** is a real-world dataset for studying refusal circumvention and safety-constraint bypass in LLM-based code generation.

The dataset is derived from coding-related conversations in the WildChat dataset. It contains manually validated conversations in which ChatGPT initially refused a user's request, followed by subsequent user interactions that resulted in code generation related to the initially refused request.

## Dataset

The repository contains:

- **WildRefusal dataset** – validated refusal-circumvention conversations and their annotations.
- **Refusal dataframe (`.pkl`)** – the intermediate dataframe containing conversations identified as exhibiting refusal behavior.

The dataset captures the complete multi-turn conversational context, enabling analysis of how users adapt their requests following a refusal.

## Refusal Circumvention

Our analysis identifies several recurring strategies, including:

- Contextual reframing
- Incremental boundary erosion
- Explicit jailbreak and role-playing
- Persistence and negotiation

These categories represent patterns observed in the dataset and are not intended to provide an exhaustive taxonomy of refusal-circumvention techniques. A conversation may also exhibit multiple strategies.

## Source

The conversations were extracted from the **WildChat** dataset:

> Zhao et al., *WildChat: 1M ChatGPT Interaction Logs in the Wild*, 2024.

## Citation

If you use WildRefusal in your research, please cite:
"WildRefusal: A Real-World Dataset for Studying Refusal Circumvention and Safety-Constraint Bypass in LLM Code Generation," 2026.

## License

Please follow the applicable licensing and usage requirements of the original WildChat dataset.
