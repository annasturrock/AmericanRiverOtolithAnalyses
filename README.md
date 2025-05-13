**FILE: Adult_otolith_Sr8786_and_lens_d34S_with_metadata	**
Otolith strontium isotope profile (time series) data for adult post-spawned adults sampled in the American River natural spawning grounds in 2014-2021, and - for individuals where their eye lens sulphur isotopes were pre-screened to see if they were likely hatchery vs wild - also teh natal lens d34S value.

**Sample_ID**	Fish ID
**Petro_no**	Petrographic slide location
**Distance_no**	Spot number (0.5 values reflect 'respots' done after main line)
**Distance_um**	Otolith distance from core to dorsal edge along a standardised 90 degree angle in microns
**Sr8786_norm**	Otolith Sr8786 measurement 
**SE2**	Standard error around spot measurement multiplied by 2
**SrV**	Strontium concentration inferred by the strontium voltage (note that this varies with instrument performance so we used the relative SrV percent within fish for FW exit estimation)
**Spot_size_um**	Spot diameter in microns
**Rep_rate_hz**	Repetition rate of laser in Hertz
**Dwell_time_sec**	Spot dwell time in seconds
**Power_percent**	Laser power in percent
**Analysis_date**	Analysis date
**Analysis_time**	Analysis time
**Notes**	Sample notes
**Sample_type**	Sample type
**respot**	Whether the spot was done sequentially or added in after between two spots to improve temporal resolution (i.e. a 'respot')
**agency_id**	Agency fish ID
**collect_date**	Collection date of fish
**site_id**	Site information
**fork_length_cm**	Fish fork length in centimeters
**sex**	Fish sex if known
**Escap_yr**	Escapement year (if sampled in January this would be collection year minus 1)
**Exog_score**	Mean exogenous feeding check score (1 = indistinct [ hatchery ], 2 = distinct [ wild ], 1.5 = unreadable)
**N_reads**	Number of different estimates of the exogeneous feeding check score
**AME**	Probability of RF assignment as American River (wild) origin
**NIH**	Probability of RF assignment as Nimbus Hatchery (hatchery) origin
**NATLOC_new**	Updated natal location assignment (based on RF + exogeneous feeding check score + sometimes also lens d34S)
**NATLOC_simple**	Updated natal location assignment simplified to AME, NIH or stray
**lens_natal_d34S**	Lens d34S of the natal region (if analysed)
**HW**	Simplified hatchery vs wild assignment
**Return_age**	Age at return based on scale reads
**aged**	If the scales were read this is 'Y', if they were unavailable this is 'n' (and the fish assumed to be 3 years old). If no scales were available but the fish was < or > the conservative 2 and 4 year old size limits reported in the paper, this indicates that the fish age was updated from 3 years old based on size
**Age_use**	Final age used to estimate outmigration year
**Outmig_year**	Estimated outmigration year (Escapement year - age + 1 as fall run salmon leave freshwater the spring after they are born)
	
	
**FILE: Juvenile_otolith_Sr8786_with_metadata	**
Otolith Sr8786 profile (time series) data for juveniles sampled in 2014-2019 as part of the DJFMP sampling effort in the California Central Valley Delta.

**Sample_ID**	Fish ID
**Petro_no**	Petrographic slide location
**Outmig_yr**	Year sampled (i.e. outmigration year)
**collect_method**	Collection method (kdtw = Kodial Trawl at Sherwood Harbor, mwtr = Midwater Trawl at Chipps Island, sein = beach seine)
**Site.Name**	Collection site name
**Region**	Collection region
**site_lat**	Collection site latitude in decimal degrees
**site_long**	Collection site longitude in decimal degrees
**month**	Collection month
**jday**	Collection Julian day
**Date**	Collection date
**fork_length**	Collection fork length in mm (of frozen then thawed sample)
**weight**	Collection weight in g (of frozen then thawed sample)
**mean_exog**	Mean exogenous feeding check score (1 = indistinct [ hatchery ], 2 = distinct [ wild ], 1.5 = unreadable)
**Spot_no**	Spot number (0.5 values reflect 'respots' done after main line)
**Distance_um**	Otolith distance from core to dorsal edge along a standardised 90 degree angle in microns
**Sr8786_norm**	Otolith Sr8786 measurement 
**SE2**	Standard error around spot measurement multiplied by 2
**SrV**	Strontium concentration inferred by the strontium voltage (note that this varies with instrument performance so we used the relative SrV percent within fish for FW exit estimation)
**HW**	Simplified hatchery vs wild assignment
**NATLOC_new**	Updated natal location assignment (based on RF + exogeneous feeding check score)
**fork_length_cm**	Fork length in centimeters
**AME_non_AME**	Simplified AME vs non AME assignment
	
	
**FILE: AME_assigned_juvs_and_adults_outmig_sizes	**
Compiled data for juveniles and adults assigned as American River origin with their estimated natal and freshwater exit sizes based on otolith Sr8786 and/or SrV. 

**Sample_ID**	Fish ID
**Location**	Collection site name
**Region**	Collection region
**Capture_date**	Collection date
**collect_method**	Collection method (kdtw = Kodial Trawl at Sherwood Harbor, mwtr = Midwater Trawl at Chipps Island, sein = beach seine)
**Escap_yr**	Escapement year (if sampled in January this would be collection year minus 1)
**Outmig_yr**	Known (juveniles) or estimated (adults) outmigration year. For adults this is estimated as escapement year - estimated age + 1 as fall run salmon leave freshwater the spring after they are born
**collection_julian_day**	Collection Julian day
**capture_fork_length_juvs_mm**	Collection fork length in mm (of frozen then thawed sample)
**mean_exog**	Mean exogenous feeding check score (1 = indistinct [ hatchery ], 2 = distinct [ wild ], 1.5 = unreadable)
**time_bin_use**	For juveniles were they collected before or after Julian day 90? (used to increase representativeness of otolith sample relative to raw catch)
**NATLOC_new**	Updated natal location assignment
**WYlabel**	Water year label (including sample size)
**life_stage**	Life stage of the fish sampled
**Phenotype**	Migratory phenotype (early < 46mm FL at natal exit, late > 46 mm FL at natal exit)
**WYT**	Water year type for the outmigration year (available at CDEC)
**Natal_Exit_um**	Estimated otolith distance at natal exit in microns
**FWDist_um**	Estimated otolith distance at freshwater exit in microns
**Natal_exit_FL_mm**	Estimated fish fork length at natal exit in mm
**FW_exit_FL_mm**	Estimated fish fork length at freshwater exit in mm
