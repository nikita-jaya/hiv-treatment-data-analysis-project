# HIV Treatment Data Analysis Project

*Completed as a project for Carnegie Mellon University's 36617 Graduate Linear Models Course*

While there is existing research on the effects of human immunodeficiency virus (HIV) treat-
ment of the survival among patients with advanced HIV, there are still gaps in the knowledge
relating to prolonged clinical benefit and the effects of the stage of the disease and the prior
HIV therapy on the eﬀicacy of certain HIV treatments. It is known that Drug A improves sur-
vival among patients with advanced HIV and slows the progression of disease in patients with
little to no symptoms. We hypothesize that there exists prolonged clinical effect for patients
with less advanced patients. Research shows that effective treatment of HIV disease will likely
require combination therapy, but we hypothesize that there is a difference in responses to HIV
therapy according to the stage of the disease and extend of prior HIV drug exposure.
To address these issues, this analysis uses data from a randomized clinical trial that compared
monotherapies with Drug A alone or Drug B along with combination therapies – such as Drug
A and Drug B together or Drug A and Drug C together – in adults infected with HIV. The
following questions are explored:

• Do responses to HIV therapy vary according to the stage of the disease?


• Do responses to HIV therapy vary according to the extent of prior HIV drug exposure?

• Is there a prolonged clinical benefit from drug intervention for patients with less advanced
HIV disease?

It should be noted that not all initial patients were treated for the entirety of the trial, so the
causal conclusions of this analysis are conditional on the assumption of no confounding based
on this censoring effect. CD4 cells are white blood cells that fight infection, and CD8 are
suppressor cells that complete the immune response. A normal CD4/CD8 ratio is 2.0 that is
higher than 2 indicates a strong immune system while a ratio is less than 1 possibly indicates
HIV, AIDS if the CD4 count is less than 200/mm or other serious problems. In addition,
we will use the ratio of CD4 to CD8 cells and the difference in CD4 cell count across the
study to assess stage of HIV disease. CD4 cells are helper cells, which lead the attack against
1
infections, and CD8 are suppressor cells, which complete the immune response, so they are
potential confounders.

This analysis determined that following conclusions. Response to HIV therapy do vary ac-
cording to stage of the disease, and patients with less advanced stages of the disease have a
more positive response to the HIV therapy. Responses to HIV therapy also vary according
to the extent of prior HIV drug exposure to a statistical significant degree. There is positive
prolonged clinical benefit from drug intervention for patients with less advanced HIV disease
based on the different of their CD4 cell count.
