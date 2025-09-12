<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import StakeholderGrid from "$lib/components/layout/StakeholderGrid.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Transparency by default",
			description: "We openly share our operations manual, pricing, and working methods. You'll always know what to expect from our structured weekly rhythm and monthly reviews."
		},
		{
			title: "Quality over growth",
			description: "We never sacrifice work quality, mental health, founder relationship, or client trust for aggressive scaling. Fewer projects means deeper attention to every detail."
		},
		{
			title: "Collaborative methodology",
			description: "Our 4-step process—Research, Explore, Execute, Present—turns experimentation into systematic innovation through shared Slack channels and documented decisions."
		},
		{
			title: "Modern craft meets youthful perspective",
			description: "At eighteen, we built the design studio we wished existed—combining digital nativity with methodical craft processes that established agencies often lack."
		}
	];
</script>

<SecondaryHero
	title="Modern interfaces, built with care"
	subtitle="Thoughtful design for startups that want to stand out"
	imageSrc="/generated/image-two-young-professionals-one-male-and-one.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"At eighteen, we tried to design our first product—and found nothing but bloated agencies, vague visuals, and lifeless templates. Everything felt rushed or recycled. What we wanted was modern design that actually made the product better. So we built the studio we wished existed.",
		"We start by understanding your product goals, not just your screens. Then we explore, refine, and build with weekly structure: Monday planning, midweek updates, Friday feedback. Every interaction is intentional. Every decision is documented. No noise—just progress.",
		"We take on fewer projects to do better work. Our growing network of 50+ premium clients trusts us because we never sacrifice work quality, mental health, founder relationship, or client trust. We're not just designing interfaces—we're transforming how startups approach design as their competitive advantage."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	stakeholderType="team"
	title="Our founders."
	subtitle="Two partners, one vision."
	stakeholders={[
		{
			name: "Henor Kelmendi",
			position: "Co-founder",
			bio: "Experienced the challenge of creating modern, thoughtful interfaces at eighteen. Focuses on design clarity and understanding emerging trends for startup products.",
			image: "/generated/image-a-portrait-of-a-young-nordic-male-entrep.webp"
		},
		{
			name: "Álfar Smári",
			position: "Co-founder", 
			bio: "Built a design studio from scratch at eighteen with focus on interface craft. Brings early entrepreneurial experience and commitment to thoughtful design details.",
			image: "/generated/image-a-portrait-of-a-young-nordic-male-entrep.webp"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Ready to transform your interface?"
	subtitle="Week-by-week subscriptions you can pause anytime"
	description="Join 50+ startup founders who chose modern, thoughtful design over generic templates. Our structured process and transparent operations eliminate agency bloat while delivering the quality your product deserves."
	imageSrc="/generated/image-a-modern-startup-founder-stands-confiden.webp"
/>
