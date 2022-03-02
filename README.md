# AffinityAnalysis
UK Grocery Retailer Affinity

Definitions
Support is the relative frequency that the rules show up. In many instances, you may want to look for high support in order
to make sure it is a useful relationship. However, there may be instances where a low support is useful if you are trying to
find “hidden” relationships.

Confidence is a measure of the reliability of the rule. A confidence of .5 in the above example would mean that in 50% of the
cases where Diaper and Gum were purchased, the purchase also included Beer and Chips. For product recommendation, a 50%
confidence may be perfectly acceptable but in a medical situation, this level may not be high enough.

Lift is the ratio of the observed support to that expected if the two rules were independent (see wikipedia). The basic rule
of thumb is that a lift value close to 1 means the rules were completely independent. Lift values > 1 are generally more
“interesting” and could be indicative of a useful rule pattern.
