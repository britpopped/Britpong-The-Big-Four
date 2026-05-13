# BRITPONG

**Britpong** is a tiny browser game inspired by classic Pong, 1990s teletext, and the Big Four of Britpop.

It looks like a fictional **Britpopped Sport** broadcast from 1995.  
It plays like Pong.  
It behaves like a cup semi-final nobody asked for, but everyone understands immediately.

---

## Play the game

Choose your band.

Wait for the **Big 4 Cup** semi-final draw.

Play a first-to-seven match against one of the other Britpop giants.

The teams are:

- **Oasis**
- **Blur**
- **Pulp**
- **Suede**

---

## Live version

Once GitHub Pages is switched on, the game should appear here:

```text
https://YOUR-GITHUB-USERNAME.github.io/britpong/
```

Replace `YOUR-GITHUB-USERNAME` with your own GitHub username.

---

## Files

This project is deliberately simple.

You only need:

```text
index.html
README.md
```

The full game lives inside **index.html**.

That one file contains:

- HTML
- CSS
- JavaScript
- game logic
- animations
- desktop controls
- mobile controls
- responsive layout

No build step.  
No React setup.  
No install.  
No terminal work required.

---

## Controls

### Desktop

| Action | Control |
|---|---|
| Move up | `↑` or `W` |
| Move down | `↓` or `S` |
| Serve / pause | `Space` |
| Continue menu screens | `Enter` |
| Return to menu during match | `Esc` |

### Mobile

| Action | Control |
|---|---|
| Select band | Tap band |
| Start match | Tap button |
| Move paddle | Drag on pitch |
| Alternative movement | Use **UP** and **DOWN** buttons |

---

## How to put this on GitHub Pages

1. Create a new GitHub repository.
2. Name it:

```text
britpong
```

3. Add your game file as:

```text
index.html
```

4. Add this file as:

```text
README.md
```

5. Commit both files.
6. Open the repository **Settings**.
7. Go to **Pages**.
8. Under **Build and deployment**, choose:

```text
Deploy from a branch
```

9. Set:

```text
Branch: main
Folder: /root
```

10. Click **Save**.

GitHub will publish the game after a short delay.

---

## WordPress embed

Once the GitHub Pages version is live, you can embed Britpong in a WordPress post with an iframe.

Use a **Custom HTML** block and paste this:

```html
<iframe
  src="https://YOUR-GITHUB-USERNAME.github.io/britpong/"
  width="100%"
  height="760"
  style="border:0; max-width:100%;"
  loading="lazy"
  title="Britpong">
</iframe>
```

Replace the `src` with your actual GitHub Pages link.

---

## Best display

Britpong works on desktop and mobile.

It is best on:

- desktop
- tablet
- mobile landscape

It also works in mobile portrait, but the game area will naturally be smaller.

---

## Troubleshooting

### The page shows code instead of the game

Check the filename.

It must be:

```text
index.html
```

Not:

```text
index.txt
index.html.txt
britpong.html
```

---

### GitHub Pages says it is live, but I cannot see it

Check:

- the repository is public
- Pages is enabled
- the branch is `main`
- the folder is `/root`
- `index.html` is in the top level of the repository

Then wait a few minutes and refresh.

---

### The WordPress embed does not show

Open the GitHub Pages link directly in your browser first.

If it works there, the issue is probably the WordPress iframe block, theme, or security settings.

---

## Credits

Created for **Britpopped**.

Britpong is a fan-made browser game inspired by Pong, 1990s teletext design, and Britpop culture.

No official connection to any band, broadcaster, chart company, or elderly man in a blazer.

---

## Status

Playable.  
Silly.  
Quite possibly too much work for a Pong joke.
