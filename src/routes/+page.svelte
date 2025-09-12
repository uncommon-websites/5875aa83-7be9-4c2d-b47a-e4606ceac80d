<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
	
	// Icons
	import IconCompass from "~icons/lucide/compass";
	import IconZap from "~icons/lucide/zap";
	import IconUsers from "~icons/lucide/users";
	import IconPalette from "~icons/lucide/palette";
	import IconRocket from "~icons/lucide/rocket";
	import IconEye from "~icons/lucide/eye";
</script>

<Hero
	title="Transform brand interfaces into modern, thoughtful experiences"
	subtitle="We help startup founders create polished, user-focused products that attract users and investors through deliberate collaboration and systematic design refinement."
	imageSrc="/generated/image-a-group-of-young-startup-founders-collab.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by design-forward teams"
	logoUrls={[
		'https://cdn.brandfetch.io/framer.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/linear.app/w/400/h/400/logo',
		'https://cdn.brandfetch.io/vercel.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/notion.so/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="Manneskja transforms brand interfaces into modern, thoughtful experiences through deliberate collaboration and systematic design refinement. We partner with startup founders and product managers who need polished, user-focused design that attracts users and investors, moving beyond generic templates to create distinctive digital products. Our structured 4-step process combines youthful digital fluency with methodical craft, delivering week-by-week flexibility that grows with your business."
/>

<Testimonials
	testimonials={[
		{
			name: "Astrid Larsen",
			position: "Co-founder & CEO",
			company: "FlowTech",
			quote:
				"Manneskja transformed our confusing interface into something investors actually understood. We closed our Series A three weeks ahead of schedule after showing the new designs.",
			image: "/generated/image-a-confident-young-scandinavian-female-st.webp"
		},
		{
			name: "Kenji Nakamura",
			position: "Product Manager",
			company: "Pulse Analytics",
			quote:
				"Instead of spending months with generic templates, Manneskja delivered thoughtful design in just 4 weeks. Our user engagement increased 67% within the first month of launch.",
			image: "/generated/image-a-confident-asian-male-product-manager-i.webp"
		},
		{
			name: "Zara Okonkwo",
			position: "Founder",
			company: "Verde AI",
			quote:
				"The subscription model saved us over $40K compared to traditional agencies. When we needed to pivot our product direction, we simply paused and resumed without any penalties.",
			image: "/generated/image-a-confident-african-female-ceo-stands-fo.webp"
		}
	]}
/>

<Features
	title="Why startups choose Manneskja"
	subtitle="Modern interface design that grows with your vision"
	features={[
		{
			title: "Systematic design process",
			description: "Our proven 4-step methodology delivers thoughtful results every time. No rushed work, no missed details, just consistent excellence that attracts users and investors.",
			icon: IconCompass
		},
		{
			title: "Flexible subscription model",
			description: "Start, pause, or adjust your design partnership anytime with week-by-week flexibility. No lengthy contracts or agency bloat, just design support that adapts to your startup's rhythm.",
			icon: IconZap
		},
		{
			title: "Collaborative partnership",
			description: "Shared Slack channels and structured bi-weekly updates keep you connected to every decision. Experience true design partnership, not the black box approach of traditional agencies.",
			icon: IconUsers
		},
		{
			title: "Modern interface expertise",
			description: "Transform generic templates into distinctive, user-focused products that differentiate your startup. We create interfaces that feel modern, work intuitively, and build lasting user engagement.",
			icon: IconPalette
		},
		{
			title: "Startup-focused experience", 
			description: "Built by young entrepreneurs who understand early-stage challenges firsthand. We know what investors look for and how to balance rapid iteration with design quality.",
			icon: IconRocket
		},
		{
			title: "Nordic design clarity",
			description: "Clean, purposeful aesthetics rooted in clarity over complexity. Every interface element serves a purpose, creating products that feel effortless to use and solid to build.",
			icon: IconEye
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Ready to transform your interface?"
	subtitle="Start your design partnership today"
	description="Join 50+ startup founders who've discovered the difference thoughtful design makes. Book a discovery call this week and see how we can transform your interface into something that attracts users and investors. No lengthy contracts, just results."
	imageSrc="/generated/image-a-confident-startup-founder-standing-in-.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Book discovery call",
			variant: "primary"
		},
		{
			href: "/work",
			label: "View our work",
			variant: "secondary"
		}
	]}
/>
