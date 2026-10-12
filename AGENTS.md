<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->

- Keep shared website navigation and footer in the root route, with separate content routes for each major section, so links remain shareable and accessible.
- Keep reusable service content and page metadata helpers in a browser-safe content module to ensure consistent copy across pages.
- Keep the consultant profile and selected career history in the shared content module; describe career roles as personal experience, not consultancy client endorsements.
- Contact inquiries are handed off to the owner's business email through a mailto form; the website itself never stores or sends messages, so never claim a submission was stored or delivered by the site.
- Define visual styles and semantic color tokens in the global stylesheet and use the shared Button variants for controls.
