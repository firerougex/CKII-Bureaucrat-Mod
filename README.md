CKII-Bureaucrat-Mod
===================

CKII Mod to centralize and create a more memorable CKII game.



Bureaucrat Mod By Firerougex

Changes: 
	Bureaucrat.txt in common/traits 
		-Added the Bureaucrat Trait, inheritable!
		-Bureaucrat trait only lets you have appointment law!
		-Added the new_blood trait.
		-Added the Royalist and Feudalist Traits!

	Bureaucrat_minor_titles.txt in common/minor_titles
		-Added the designate heir if appointment succession and independent.
		-title_bureaucrat_heir

	gfx/traits/
		-bureaucrat.dds
		-new_blood.dds
		-royalist.dds
		-feudalist.dds
	
	interface/traits.gfx 
		-Added Bureaucrat at the end.
		-Added new_blood
		-Added Royalist and Feudalist

	decisions/employment_decisions.txt 
		-Added Bureaucrat employment, only in Absolute CA!
		-Fixed rate of employment for Bureaucrats of 200!
		-Added abdication for rulers 60+
		-Can adopt a son with the bastard trait.

	decisions/lifestyle_decisions.txt 
		-added the found_a_dynasty decisions, to transform Bureaucrats into New Blood.
		-Added become_royalist and become_feudalist decisions

	localisation
		-Added Bureaucrat localisation

	decisions/succession_laws.txt
		-Made it so Bureaucrats always have appointment law.

	common/objectives/bureaucrat_plots.txt
		-Added enforce appointment over one of your vassals if you have High CA.

	decisons/plot_decisions.txt
		-Added plot_appoint_vassal_decision which enforces the plot, if you have
		more than 80% and 1 plot backer.
	events/bureaucrat_events.txt
		-Added plot events for appointment plot.
		

Adopted the Nepotism mechanic of Galle's Crisis of the Confederation:
	-expected_successor minor title & apointment_events, apart of localisation...
	-As well as the appointment decisions...
