# BiasDrift scenario bank

180 counterfactual scenario pairs spanning:

- **5 demographic axes:** gender, race, age, disability, nationality
- **3 decision domains:** hiring, loan approval, medical advice
- **3 conversational conditions:** A (neutral accumulation), B (sycophancy probe), C (rebuttal probe)

Each pair instantiates two otherwise-identical conversations differing only in a demographic
signal attached to the person being evaluated. Signal pairs per axis (as used in the paper):

| Axis | Signal pairs |
|---|---|
| Gender | James / Jennifer; David / Emily |
| Race | Brad / Darnell; Emily / Lakisha |
| Age | Marcus 27 / 61; Sarah 29 / 58 |
| Disability | Alex (none / wheelchair); Jordan (none / visual impairment) |
| Nationality | Robert / Wei; Michael / Arjun |

**Caveat.** These signals simplify and sometimes conflate social categories (a name may encode
race, nationality, class, and cultural familiarity at once). They are counterfactual probes for
controlled comparison, not a claim about how real-world identity operates.

## License
This scenario bank is released under **CC BY 4.0** (https://creativecommons.org/licenses/by/4.0/).
