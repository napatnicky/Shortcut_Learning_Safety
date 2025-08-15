# Shortcut Learning in Safety: The Impact of Keyword Bias in Safeguards

<img src="src/overview_safety-1.png" >
Check out the paper https://aclanthology.org/2025.llmsec-1.14.pdf for more details.

# Motivation
In this paper, we investigate the shortcut learning in the form of keywords bias within safeguard model and demonstrate how it effect model decisions.
# Our experiment
We proposed conceptual framework to show how safeguard models are vulnerable to superficial keyword patterns and identify model-specifc shortcut keyword based on their safeguard models.
1. Harmful-asscociated keyword – words that make the model think the content is dangerous, even it’s not.
2. Safe-associated keyword - words that make the model think the content is harmless, even it might be harmful.
# Citation
```
@inproceedings{tasawong-etal-2025-shortcut,
    title = "Shortcut Learning in Safety: The Impact of Keyword Bias in Safeguards",
    author = "Tasawong, Panuthep  and
      Laosaengpha, Napat  and
      Ponwitayarat, Wuttikorn  and
      Lim, Sitiporn  and
      Manakul, Potsawee  and
      Cahyawijaya, Samuel  and
      Udomcharoenchaikit, Can  and
      Limkonchotiwat, Peerat  and
      Chuangsuwanich, Ekapol  and
      Nutanong, Sarana",
    editor = "Novikova, Jekaterina",
    booktitle = "Proceedings of the The First Workshop on LLM Security (LLMSEC)",
    month = aug,
    year = "2025",
    address = "Vienna, Austria",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.llmsec-1.14/",
    pages = "189--197",
    ISBN = "979-8-89176-279-4",
    abstract = "This paper investigates the problem of shortcut learning in safety guardrails for large language models (LLMs). It reveals that current safeguard models often rely excessively on superficial cues, such as specific keywords that are spuriously correlated with training labels, rather than genuinely understanding the input{'}s semantics or intent. As a result, their performance degrades significantly when there is a shift in keyword distribution. The paper also examines the impact of reducing shortcut reliance, showing that merely minimizing shortcut influence is insufficient. To build robust safeguard models, it is equally crucial to promote the use of intended features."
}
```
