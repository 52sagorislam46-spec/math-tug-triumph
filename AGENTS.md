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

## Game architecture
- Keep match rules and problem generation in a browser-safe game module so they can be tested independently of the interface.
- Store match history only in browser localStorage after hydration because this game explicitly uses device-local results.
- Render the tug-of-war arena as an original animated SVG so characters and rope move together without external asset dependencies.
