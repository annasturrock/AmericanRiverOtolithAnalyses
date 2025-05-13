**FILE 1**
**Adult_otolith_Sr8786_and_lens_d34S_with_metadata.csv** </p>
Otolith strontium isotope profile (time series) data for adult post-spawned adults sampled in the American River natural spawning grounds in 2014-2021, and - for individuals where their eye lens sulphur isotopes were pre-screened to see if they were likely hatchery vs wild - also the natal lens d34S value. </p>

**Sample_ID**	Fish ID </p>
**Petro_no**	Petrographic slide location </p>
**Distance_no**	Spot number (0.5 values reflect 'respots' done after main line)</p>
**Distance_um**	Otolith distance from core to dorsal edge along a standardised 90 degree angle in microns</p>
**Sr8786_norm**	Otolith Sr8786 measurement </p>
**SE2**	Standard error around spot measurement multiplied by 2</p>
**SrV**	Strontium concentration inferred by the strontium voltage (note that this varies with instrument performance so we used the relative SrV percent within fish for FW exit estimation) </p>
**Spot_size_um**	Spot diameter in microns </p>
**Rep_rate_hz**	Repetition rate of laser in Hertz </p>
**Dwell_time_sec**	Spot dwell time in seconds </p>
**Power_percent**	Laser power in percent </p>
**Analysis_date**	Analysis date </p>
**Analysis_time**	Analysis time </p>
**Notes**	Sample notes </p>
**Sample_type**	Sample type </p>
**respot**	Whether the spot was done sequentially or added in after between two spots to improve temporal resolution (i.e. a 'respot') </p>
**agency_id**	Agency fish ID </p>
**collect_date**	Collection date of fish </p>
**site_id**	Site information </p>
**fork_length_cm**	Fish fork length in centimeters </p>
**sex**	Fish sex if known </p>
**Escap_yr**	Escapement year (if sampled in January this would be collection year minus 1) </p>
**Exog_score**	Mean exogenous feeding check score (1 = indistinct [ hatchery ], 2 = distinct [ wild ], 1.5 = unreadable) </p>
**N_reads**	Number of different estimates of the exogeneous feeding check score </p>
**AME**	Probability of RF assignment as American River (wild) origin </p>
**NIH**	Probability of RF assignment as Nimbus Hatchery (hatchery) origin </p>
**NATLOC_new**	Updated natal location assignment (based on RF + exogeneous feeding check score + sometimes also lens d34S) </p>
**NATLOC_simple**	Updated natal location assignment simplified to AME, NIH or stray </p>
**lens_natal_d34S**	Lens d34S of the natal region (if analysed) </p>
**HW**	Simplified hatchery vs wild assignment </p>
**Return_age**	Age at return based on scale reads </p>
**aged**	If the scales were read this is 'Y', if they were unavailable this is 'n' (and the fish assumed to be 3 years old). If no scales were available but the fish was < or > the conservative 2 and 4 year old size limits reported in the paper, this indicates that the fish age was updated from 3 years old based on size </p>
**Age_use**	Final age used to estimate outmigration year </p>
**Outmig_year**	Estimated outmigration year (Escapement year - age + 1 as fall run salmon leave freshwater the spring after they are born) </p>
	 </p>

**FILE 2** </p>
**Juvenile_otolith_Sr8786_with_metadata.csv** </p>
Otolith Sr8786 profile (time series) data for juveniles sampled in 2014-2019 as part of the DJFMP sampling effort in the California Central Valley Delta. </p>
**Sample_ID**	Fish ID </p>
**Petro_no**	Petrographic slide location </p>
**Outmig_yr**	Year sampled (i.e. outmigration year) </p>
**collect_method**	Collection method (kdtw = Kodial Trawl at Sherwood Harbor, mwtr = Midwater Trawl at Chipps Island, sein = beach seine)</p>
**Site.Name**	Collection site name</p>
**Region**	Collection region</p>
**site_lat**	Collection site latitude in decimal degrees</p>
**site_long**	Collection site longitude in decimal degrees</p>
**month**	Collection month</p>
**jday**	Collection Julian day</p>
**Date**	Collection date</p>
**fork_length**	Collection fork length in mm (of frozen then thawed sample)</p>
**weight**	Collection weight in g (of frozen then thawed sample)</p>
**mean_exog**	Mean exogenous feeding check score (1 = indistinct [ hatchery ], 2 = distinct [ wild ], 1.5 = unreadable)</p>
**Spot_no**	Spot number (0.5 values reflect 'respots' done after main line)</p>
**Distance_um**	Otolith distance from core to dorsal edge along a standardised 90 degree angle in microns</p>
**Sr8786_norm**	Otolith Sr8786 measurement </p>
**SE2**	Standard error around spot measurement multiplied by 2</p>
**SrV**	Strontium concentration inferred by the strontium voltage (note that this varies with instrument performance so we used the relative SrV percent within fish for FW exit estimation)</p>
**HW**	Simplified hatchery vs wild assignment</p>
**NATLOC_new**	Updated natal location assignment (based on RF + exogeneous feeding check score)</p>
**fork_length_cm**	Fork length in centimeters</p>
**AME_non_AME**	Simplified AME vs non AME assignment</p>
	 </p>
	
**FILE 3**</p>
**AME_assigned_juvs_and_adults_outmig_sizes.csv**</p>
Compiled data for juveniles and adults assigned as American River origin with their estimated natal and freshwater exit sizes based on otolith Sr8786 and/or SrV. </p>

**Sample_ID**	Fish ID</p>
**Location**	Collection site name</p>
**Region**	Collection region</p>
**Capture_date**	Collection date</p>
**collect_method**	Collection method (kdtw = Kodial Trawl at Sherwood Harbor, mwtr = Midwater Trawl at Chipps Island, sein = beach seine)</p>
**Escap_yr**	Escapement year (if sampled in January this would be collection year minus 1)</p>
**Outmig_yr**	Known (juveniles) or estimated (adults) outmigration year. For adults this is estimated as escapement year - estimated age + 1 as fall run salmon leave freshwater the spring after they are born</p>
**collection_julian_day**	Collection Julian day</p>
**capture_fork_length_juvs_mm**	Collection fork length in mm (of frozen then thawed sample)</p>
**mean_exog**	Mean exogenous feeding check score (1 = indistinct [ hatchery ], 2 = distinct [ wild ], 1.5 = unreadable)</p>
**time_bin_use**	For juveniles were they collected before or after Julian day 90? (used to increase representativeness of otolith sample relative to raw catch)</p>
**NATLOC_new**	Updated natal location assignment</p>
**WYlabel**	Water year label (including sample size)</p>
**life_stage**	Life stage of the fish sampled</p>
**Phenotype**	Migratory phenotype (early < 46mm FL at natal exit, late > 46 mm FL at natal exit)</p>
**WYT**	Water year type for the outmigration year (available at CDEC)</p>
**Natal_Exit_um**	Estimated otolith distance at natal exit in microns</p>
**FWDist_um**	Estimated otolith distance at freshwater exit in microns</p>
**Natal_exit_FL_mm**	Estimated fish fork length at natal exit in mm</p>
**FW_exit_FL_mm**	Estimated fish fork length at freshwater exit in mm</p>
