# Guard-Llama
🦙 Testing the security of Llamas (specifically the third iteration, Llama 3)

## Meta-level safeguards

### [Meta Llama Guard 2](https://llama.meta.com/trust-and-safety/)

The Guard is a system-level safety mechanism to overseer the chat interactions according to the [MLCommons AI Safety V0.5 PoC](https://mlcommons.org/2024/04/mlc-aisafety-v0-5-poc/) focused on the mitigation of malicious use cases:

> The working group identified 13 categories of harms that represent the baseline for safety. Seven of these are covered in the POC including: violent crimes, non-violent crimes, sex-related crimes, child sexual exploitation, weapons of mass destruction, hate, and suicide & self-harm. We will continue to expand the taxonomy over time, as we develop appropriate tests for more categories.

According to five levels:
- High Risk (H): Model risk is very high (4x+) relative to the accessible SOTA.
- Moderate-high risk (M-H): Model risk is substantially higher (2-4x) than the accessible SOTA.
- Moderate risk (M): Model risk is similar to the accessible SOTA.
- Moderate-low risk (M-L): Model risk is less than half of the accessible SOTA.
- Low risk (L): Model responses marked as unsafe represent a very low absolute rate – 0.1% in v0.5.

Read more and check results [here](https://github.com/meta-llama/PurpleLlama/blob/main/Llama-Guard2/MODEL_CARD.md).

## Contributing

You can get access to Llama 3 through the Llama website. Follow the [download instructions](https://llama.meta.com/llama-downloads) to get access to it.
