# Alfred WCAG Workflow

This [Alfred](https://www.alfredapp.com/) Workflow allows you to search through Web Content Accessibility Guidelines (<abbr>WCAG</abbr>) Success Criterion (<abbr>SC</abbr>), and then copy a link to the selected SC to your clipboard or open its Understanding page in your default browser. 

The Workflow uses [WCAG 2.1](https://www.w3.org/TR/WCAG21/), which is the current W3C Recommendation at the time of this Workflow's last published update.

## How to install this Workflow

Requires Alfred and the [Alfred Powerpack](https://www.alfredapp.com/powerpack/).

1. Download the latest release from this repo.
2. Open the `alfred-wcag-workflow.alfredworkflow` file wherever your browser saves downloaded files.
3. Activate the "Install" button on the import prompt displayed after opening the `.workflow` file.

## How to use this Workflow

1. Type `wcag`, the Workflow filter keyword, and then <kbd>Space</kbd>.
2. Begin typing either the SC's number (ex: `2.5.3`) or its title (`Label in Name`). The Workflow's results will update as you refine your query.
3. Take action on a result by highlighting it in the Alfred command palette results and using one of the following interactions:
  * <kbd>Enter</kbd>/click: Open the SC's Understanding page URL in the default browser.
  * <kbd>Option</kbd> + <kbd>Enter</kbd>: Copy the SC's Understanding page URL to the clipboard.
  * <kbd>Command</kbd> + <kbd>Enter</kbd>: Copy the SC's number, name, and link to its Understanding page as a HTML link.

## How to report a problem with this Workflow

Submit an issue to the GitHub issue tracker using the [bug report issue template]().

## How to suggest new features and functionality for this Workflow

Submit an issue to the GitHub issue tracker using the [feature suggestion issue template]().

### Features I would like help with

- [ ] Opening the base WCAG 2.1 URL when no filter keyword is entered and <kbd>Enter</kbd> is pressed.
- [ ] Logic for showing a custom icon for each of the four POUR categories (Percievable, Operable, Understandable, Robust).

## FAQ

### Why isn't this Workflow listed in the official Alfred Workflow Gallery or Packal?

I mainly use this Workflow for my job, and do not have the resources to provide full-blown community support. Hopefully the Workflow in its current form is helpful to you if you find yourself needing something like this.

### Can you make a Raycast extension?

Migrating from Quicksilver to Alfred was enough work on its own. I'm not really interested in uprooting things again for another quick launcher.

### Will you update this when WCAG updates?

I am hoping to be either retired or dead by the time WCAG 3.0 is published, but will otherwise support WCAG updates.

## License 

This Workflow is licensed using [the MIT License](https://github.com/ericwbailey/alfred-wcag-workflow/blob/main/LICENSE). 

The Web Content Accessibility Guidelines content are copyright ® W3C. [W3C liability, trademark and document use rules apply](https://www.w3.org/policies/#Copyright).
