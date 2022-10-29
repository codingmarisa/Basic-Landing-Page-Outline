# Assignment: Basic Landing Page Outline
## Provided Design Mockup
Two images are supplied in preparation for the website development:
1. Full Color Website Mockup [link](https://github.com/codingmarisa/Basic-Landing-Page-Outline/blob/main/images/website-mockup.png?raw=true)
2. Color & Font Selections [link](https://github.com/codingmarisa/Basic-Landing-Page-Outline/blob/main/images/font-and-color-selections.png?raw=true)
The developer is expected to use these resources to create a page that meets the design expectations.
## Proposed Deviation from Submitted Design
### Potential Design Issue
No color selection is supplied for the text within the hero sign up button or the paragraph text within call-to-action section. From the design, it appears that the expected font color for the two sign up buttons is #F9FAF8. The expected font color for the call to action paragraph is #E5E7EB. Both of these colors fail an accessibility contrast test by both axe DevTools and Lighthouse. Even if these fonts are lightened to #FFF, the contract between the background color of #3882F6 does not provide adequate contrast to maintain conformity to WCAG 2.0 at Level AA (wcag143).
### Proposed Action
Although some companies only aim for Level A compliance, this level only meets the baseline of accessibility requirements and poses the risk of serving potential customers with a website that does not meet their accessibility needs. To ensure an inclusive experience, I would recommend meeting the Level AA conformity level. This ensures that the website will more than likely provide potential customers with a positive experience, which in turn could convert potential customers into current customers. Additionally, when it is considered that the offending components are those responsible for enrolling a customer, the issue carries more weight.

I propose: 
- Lightening the problematic text from #F9FAF8 and #E5E7EB to #FFF.
- Darken the background color of the Sign Up buttons and call-to-action section from #3882F6 to #186ef5.

From a stylistic perspective, the difference between these color changes are insignificant. Due to the low consequence of such a change, it is simple and reasonable to make these three small adjustments to meet Level AA conformity.

### Potential Barrier to Proposed Action
Although the changes to the above colors are minor, if these colors are in fact brand colors then this change could be seen as unreasonable. If this were the case, it would be suggested that the design team considers an alternative change that could improve the contrast ratio. If not, it may be deemed necessary by the website owner to fall short of Level AA conformity to meet brand conformity.
