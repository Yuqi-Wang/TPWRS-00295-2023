# TPWRS-00295-2023
The quasi-static time series result for both power and carbon emission flow.
(1) The power flow results are divided into four seasons, and the results in each season are separated into three folders. The last number of the file name means the index of time slot in the whole year. So the first numer is 0 in the 'power flow result in spring_1.rar' file and the last number is 105,119 in the 'power flow result in winter_3.rar' file. The meanings of the fields in the data file are given below:
omig_ess_ch: binary value, 0 if the ESS doesn't charge and 1 if the ESS charge.
omig_ess_dch: binary value, 0 if the ESS doesn't discharge and 1 if the ESS discharge.
p_sub_b: active power of substation (PCC) in p.u.
q_sub: reactive power of substation (PCC) in p.u.
p_ch: charging power of ESS in p.u.
p_dch: discharging power of ESS in p.u.
gama: the cutting rate of PV units
u_bus: the square of bus voltage in p.u.
p_line: active power in line in p.u.
q_line: reactive power in line in p.u.
i_line: the square of current in line in p.u.
miu: the rate of actually injected power of PV units
q_pv: reactive power of PV units in p.u.
objection: the obtained value of the combined objective function
after_ess_soc: the SOC of ESS in the end of this time slot

(2) The carbon emission flow results are also divided into four seasons and the results in each season are separated into two folders. The last number of the file name means the index of time slot in the whole year. So the first numer is 0 in the 'carbon emission flow in spring_1.rar' file and the last number is 105,119 in the 'carbon emission flow in winter_2.rar' file. The meanings of the fields in the data file are given below, and please refer to [1] for the meanings of abbreviations:
ECEF_e: the ECEF intensity at each bus, kg/MWh
ECEF_R: the ECEF rate at each bus, kg/h
ICEF_e: the ICEF intensity at each bus, kg/MWh
ICEF_R: the ICEF rate at each bus, kg/h
BCEF_e: the BCEF intensity at each line, kg/MWh
BCEF_R: the BCEF rate at each line, kg/h
BCEL_e: the BCEL intensity at each line, kg/MWh
BCEL_R: the BCEL rate at each line, kg/h

If you have any questions about the results, please feel free to contact us yuqi_wang22@mails.tsinghua.edu.cn. We'd like to provide further clarification.

[1] C. Kang et al., "Carbon Emission Flow From Generation to Demand: A Network-Based Model," in IEEE Transactions on Smart Grid, vol. 6, no. 5, pp. 2386-2394, Sept. 2015.
