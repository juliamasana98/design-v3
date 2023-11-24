---
Title: JavaScript
Description: Page about JavaScript
Template: technology
---
 <h1>JavaScript</h1>

JavaScript är ett programmeringsspråk som främst används för att göra webbsidor interaktiva. Det körs oftast direkt i användarens webbläsare och används för att manipulera och ändra webbsideinnehåll i realtid. JavaScript är ett mångsidigt språk som stöder olika programmeringsparadigm och har blivit en grundläggande teknologi för webbutveckling, från enkla interaktioner som validering av formulär till avancerade applikationer med dynamiskt innehåll och användargränssnitt.


<pre><code class="language-javascript">const MailPace = require('@mailpace/mailpace.js');
const client = new MailPace.DomainClient('API_TOKEN_HERE');

client
	.sendEmail({
		from: 'test@test.com',
		to: 'test@test.com',
		subject: 'test',
		htmlbody: 'HTML Email',
	})
	.then((r) => {
		console.log(r);
	});</code></pre>
