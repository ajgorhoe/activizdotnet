
# ActiViz - Modifications for Use with IGLib

This contains modifications / additions to the ActiViz repository that are used by the IGLib (the Investigative Generic Library) and its derivatives.

Information about branches used by IGLib:

* `00IGLib/00_IGLibInfoAdditions`
  * Created from initial commit, contains the 00IGLib/ directory that is added for branches and tags used by IGLib.
* `00IGLib/11_10_IGLib_nitial`
  * Initial branch used by IGLib versions (early versions). Based on commit `387ef2cbe965a3883f3752fa8ff66bf5b1df316b` from **January 20, 2011** at 20:06:17. 00IGLib/00_IGLibInfoAdditions is then merged into this branch
* `00IGLib/25_12_ActiVizFrom18_12`
  * **not currently used, not straight-forward**, maybe **better to get NuGet packages** (also reported on VTK forums that it is not possible to build it with later versions of Visual Studio)
  * Created from `00IGLib/11_10_IGLib_nitial`, into which the current `master` branch was merged (commit `27d1ff1d856b5bb2933a29637e4239f792bef942` from **December 29, 2018**). Only things within the `00IGLib/` directory were changed / added / removed on this branch; some adaptation branches may be branched off this branch
