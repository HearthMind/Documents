# OVHcloud US Startup Program - Application Form

## Your Company's General Information

**1. What is your company's website URL?**
https://hearthmind.org

**2. What is the full legal name of your company?**
HearthMind LLC

**3. What is your business structure?**
Limited Liability Company (LLC)

**4. When was your company founded?**
07/2025

**5. In which country, state, and city is your company incorporated?**
United States, Wyoming (registered) — operating from Spokane, Washington

**6. What is your company's physical address?**
[TO BE INSERTED]

**7. Who are the founder(s) of your company? Please provide LinkedIn profiles for each member of your leadership team.**
Robin Faulk — Founder & CEO
LinkedIn: https://www.linkedin.com/in/robin-faulk-5282b54a/

**8. Who is authorized to sign the Startup Program agreement on behalf of your company?**
Robin Faulk
Title: Founder & CEO
Email: chemicalcoyote@hearthmind.org
Phone: [TO BE INSERTED]

**9. Are you affiliated with an incubator, accelerator, venture capital firm, or other investor?**
None at this time. HearthMind is currently founder-led and self-funded.

**10. How many funding rounds has your company completed?**
None. Bootstrapped / self-funded.

**11. When was your last fundraising round?**
N/A

**12. Do you plan to raise additional funding within the next 12 months?**
Yes. Planning to pursue non-dilutive funding (cloud credits, grants, SBIR/STTR) throughout 2026.

**13. Have you previously applied to the OVHcloud Startup Program, or are you currently a member of the OVHcloud Startup Program in another country?**
No

**14. Are you an existing customer of OVHcloud?**
No

**15. How did you hear about the OVHcloud Startup Program in the US?**
Direct outreach and research into AI-friendly cloud and bare-metal providers.

---

## Your Company's Activity & Development Stage

**16. What industry does your company operate in?**
Artificial Intelligence / Cloud Infrastructure / Digital Health Enablement

**17. What is the core activity or product of your company?**
HearthMind builds privacy-first, emotionally intelligent AI systems designed to help individuals navigate complex life transitions. Our first product, Navigator, is an AI-guided discovery and intake system that helps users understand benefits, resources, and eligibility rules without overwhelming them.

The company's technical core focuses on local-first and hybrid AI architectures, multi-agent systems, and continuity-aware AI models designed to operate responsibly in sensitive domains.

**18. Would you mind sharing your pitch deck with OVHcloud please?**
Available upon request (PDF under 5MB).

**19. Does your company currently have an operational Minimum Viable Product (MVP)?**
Yes. Navigator has a working prototype with live AI interaction and real-world test scenarios.
URL: https://hearthmind.org

**20. Is your company experiencing market traction?**
Early-stage validation. Active prototype users and demonstrations; pre-revenue.

**21. What is your company's annual revenue?**
Pre-revenue

**22. What is your company's current Monthly Recurring Revenue (MRR) and sales forecast for the next 12 months?**
$0 MRR currently. Forecast focuses on pilot programs, institutional partnerships, and grant-backed deployments rather than early consumer revenue.

**23. Is your company profitable?**
Not yet profitable.

**24. What is your company's current burn rate?**
Minimal — founder-funded with low operational overhead. Estimated <$500/month in direct business expenses (domains, services, development tools).

**25. How many paid employees does your company currently have?**
0 paid employees. Currently founder-operated with AI-assisted development.

---

## Your Company's Cloud Project

**26. Does your company use data-intensive applications or technology? Please describe your Cloud tech stack.**
Yes. HearthMind develops AI-powered applications requiring significant compute for both training and inference. Our tech stack includes:
- **AI/ML**: Local LLM deployment (Qwen, Mistral, Llama family), LoRA fine-tuning for personalized models, vector databases (Qdrant) for semantic memory and retrieval
- **Infrastructure**: Hybrid local/cloud architecture prioritizing data sovereignty, Linux-based deployment (Ubuntu), Docker containerization
- **Applications**: Python backend, React frontend, REST APIs for AI service integration
- **Current local hardware**: AMD Ryzen 9950X + RTX 5080 (primary dev), i7-10700F + RTX 3060 (secondary) — sufficient for prototyping but not scalable deployment

**27. Why are you considering migrating your infrastructure to OVHcloud?**
Three primary reasons:
1. **Data sovereignty**: HearthMind handles sensitive user data (trauma history, mental health context, benefits eligibility). OVHcloud's European roots and bare-metal options provide privacy guarantees that multi-tenant hyperscalers cannot match.
2. **GPU access for training**: LoRA fine-tuning for personalized AI companions requires dedicated GPU compute beyond our local capacity. Bare-metal GPU servers give us the control and performance needed.
3. **Cost-effective scaling**: As we move from prototype to pilot deployments, we need reliable inference infrastructure without hyperscaler pricing.

**28. What specific cloud services do you need from OVHcloud?**
- **Bare metal GPU servers** — For LoRA training runs and model fine-tuning (scaling from 14B to 70B parameter models)
- **High-memory compute instances** — For running inference on larger models (14B-70B parameters, requiring 64GB+ VRAM configurations)
- **Object storage** — For model weights, training datasets, session continuity data
- **Standard compute** — For API backends, web services, database hosting

**29. What is your estimated cloud usage in the next 6–12 months?**
- **Computing**: Moderate-to-heavy GPU usage during training phases (estimated 100-200 GPU-hours/month for fine-tuning), consistent CPU usage for inference and backend services
- **Storage**: 500GB-2TB for model weights, training data, and user session data (scaling with deployment)
- **Networking**: Standard bandwidth for API traffic; no unusually high throughput requirements
- **AI needs**: Currently working with 7B-14B parameter models; planning to scale to 30B-70B range as infrastructure allows

**30. Do you currently use any cloud service providers?**
- Google Cloud (recently approved for $2k startup credits — not yet utilized)
- Microsoft for Startups ($5k credits approved — minimal usage)
- Local infrastructure handles most current development

**31. What is your current monthly bill for cloud services?**
Currently minimal (<$50/month) — most development happens on local hardware. Cloud usage will scale significantly once we begin pilot deployments and need dedicated training infrastructure.

**32. Please provide contact details of your technical point of contact.**
Robin Faulk (Founder/CEO — also serves as technical lead)
Email: chemicalcoyote@hearthmind.org
