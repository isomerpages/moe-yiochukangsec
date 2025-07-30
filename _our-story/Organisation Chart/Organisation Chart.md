---
title: Organisation Chart
permalink: /our-story/Organisation-Chart/Organisation-Chart/
description: ""
third_nav_title: Organisation Chart
variant: markdown
---
<style>

  .yck-component .yck-nav-bar {
      display: flex;
      justify-content: space-around;
      padding: 1em 0;
      position: relative;
  }
  .yck-component .yck-nav-bar a {
        text-decoration: none;
        color: inherit; /* Inherit text color */
    padding-bottom: 0.5em;
     position: relative;
   }


    .yck-component .yck-nav-bar a::after {
         content: '';
         position: absolute;
         left: 0;
        right: 100%;
         bottom: 0;
         height: 2px;
         background-color:  #4372d6; /* Highlight Color */
         transition: right 0.5s ease-in-out; /* Transition on right for fade in from left */
     }

    .yck-component .yck-nav-bar a:hover::after {
       right: 0;
     }

.ken-burns-container {
            max-width: 100%;
            height: auto;
            overflow: hidden;
            position: relative;
        }

        .ken-burns-image {
            width: 100%;
            height: 100%;
            object-fit: cover;
            animation: kenBurns 30s ease-in-out infinite alternate;
        }

        @keyframes kenBurns {
            from {
                transform: scale(1);
            }
            to {
                transform: scale(1.3);
            }
        }

.wrapper {
    width: 100%;
    background-color: #fff;
    display: flex;
    justify-content: center;
    padding: 20px;
}

/* Main container for the entire organizational chart */
.org-chart {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 100%;
    max-width: 1600px;
    /* Allows for a wider chart */
}

/* Styling for major section titles like "School Leaders" */
.section-title {
    font-size: 1.8em;
    font-weight: bold;
    margin-top: 30px;
    margin-bottom: 20px;
    color: #222;
    border-bottom: 3px solid #555;
    padding-bottom: 8px;
    width: 100%;
    text-align: center;
}

/* Container for a group of people, e.g., all school leaders */
.person-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    width: 100%;
    margin-bottom: 25px;
    position: relative;
    /* Needed for the pseudo-element connector line */
}

/* A simple vertical line connecting a section title to its content below */
.person-container::before {
    content: '';
    position: absolute;
    top: -15px;
    /* Positioned just below the title */
    left: 50%;
    transform: translateX(-50%);
    width: 2px;
    height: 15px;
    background-color: #777;
}

/* Styling for department and staff group containers */
.department,
.staff-group {
    width: 100%;
    margin-bottom: 30px;
    padding: 15px;
    border: 1px solid #d0d0d0;
    border-radius: 8px;
    background-color: #fdfdfd;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
}

/* Titles for individual departments or non-teaching staff groups */
.department-name,
.group-name {
    font-size: 1.4em;
    font-weight: bold;
    color: #333;
    margin-bottom: 15px;
    text-align: center;
    border-bottom: 1px dashed #aaa;
    padding-bottom: 10px;
}

/* Grid layout for displaying people within a department or group */
.people-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 10px;
    /* Provides spacing between individual person cards */
}

/* Individual card for each person */
.person {
    background-color: #fff;
    border: 1px solid #ccc;
    border-radius: 6px;
    padding: 10px 15px;
    margin: 5px;
    text-align: center;
    min-width: 160px;
    max-width: 200px;
    box-shadow: 1px 1px 3px rgba(0, 0, 0, 0.1);
    flex-grow: 1;
    /* Prevents cards from growing to fill space */
    flex-shrink: 0;
    /* Prevents cards from shrinking */
    flex-basis: calc(20% - 10px);
    /* Aims for 5 cards per row, adjusting for gap */
}

/* Name of the person */
.person-name {
    font-size: 1em;
    font-weight: bold;
    margin-bottom: 4px;
    color: #333;
}

/* Title/role of the person */
.person-title {
    font-size: 0.85em;
    color: #555;
    margin-bottom: 8px;
    /* Add some space before the details tag */
}

.person details {
    font-size: 0.8em;
    cursor: pointer;
}

/* --- Tier-Specific Styling --- */

/* Special styling for school leader cards */
.school-leaders .person {
    background-color: #e0eafc;
    border-color: #abc4ff;
    flex-basis: calc(33% - 20px);
    /* Aims for 3 leaders per row */
}

/* Special styling for key personnel cards */
.key-personnel .person {
    background-color: #dcf0dc;
    border-color: #a0c0a0;
    flex-basis: calc(33.33% - 10px);
    /* Aims for 3 per row */
}

/* Styling for teaching staff cards within departments */
.department .person {
    background-color: #fff5e6;
    border-color: #ffd5ab;
    flex-basis: calc(25% - 10px);
    /* Aims for 4 per row */
}

/* Styling for non-teaching staff cards within groups */
.staff-group .person {
    background-color: #e6f2ff;
    border-color: #adccef;
    flex-basis: calc(25% - 10px);
    /* Aims for 4 per row */
}

/* --- Responsive Adjustments for Different Screen Sizes --- */

@media (max-width: 1200px) {
    .person {
        flex-basis: calc(25% - 10px);
        /* 4 cards per row */
    }

    .school-leaders .person {
        flex-basis: calc(50% - 20px);
        /* 2 leader cards per row */
    }
}

@media (max-width: 900px) {
    .person {
        flex-basis: calc(33.33% - 10px);
        /* 3 cards per row */
    }
}

@media (max-width: 600px) {
    .person {
        flex-basis: calc(50% - 10px);
        /* 2 cards per row */
    }

    .department-name,
    .group-name {
        font-size: 1.2em;
    }

    .section-title {
        font-size: 1.5em;
    }
}

@media (max-width: 400px) {
    .person {
        flex-basis: calc(100% - 10px);
        /* 1 card per row */
    }
}
</style>
<div class="yck-component">
    <nav class="yck-nav-bar">
			  <h6><a href="#School-Leaders">SCHOOL LEADERS</a></h6>
<h6><a href="#Key-Personnel">KEY PERSONNEL</a></h6>
<h6><a href="#Teaching-Staff">TEACHING STAFF</a></h6>
<h6><a href="#Non-teaching-Staff">NON-TEACHING STAFF</a></h6>

   </nav>
</div>
<div class="wrapper">
                                        <div class="org-chart">
                                            <div class="section-title" id="School-Leaders">School Leaders</div>
                                            <div class="person-container school-leaders">
                                                <div class="person">
                                                    <div class="person-name">Mrs Chow (Betty Chang)</div>
                                                    <div class="person-title">PRINCIPAL</div>
                                                    <details>
                                                        <summary>Email Address:</summary>betty_chang@moe.edu.sg
                                                    </details>
                                                </div>
                                                <div class="person">
                                                    <div class="person-name">Mr Kevin Lim Hock Chye</div>
                                                    <div class="person-title">VICE-PRINCIPAL</div>
                                                    <details>
                                                        <summary>Email Address:</summary>lim_hock_chye_kevin@moe.edu.sg
                                                    </details>
                                                </div>
                                                <div class="person">
                                                    <div class="person-name">Mr Pek Xu Hao Alvin</div>
                                                    <div class="person-title">VICE-PRINCIPAL</div>
                                                    <details>
                                                        <summary>Email Address:</summary>pek_xu_hao_alvin@moe.edu.sg
                                                    </details>
                                                </div>
                                            </div>
                                            <div class="section-title" id="Key-Personnel">Key Personnel</div>
                                            <div class="person-container key-personnel">
                                                <div class="person">
                                                    <div class="person-name">Ms Lock Hwee Hong Alicia</div>
                                                    <div class="person-title">HOD/Science</div>
                                                    <details>
                                                        <summary>Email Address:</summary>
                                                    </details>
                                                </div>
                                                <div class="person">
                                                    <div class="person-name">Ms Chong Foong Harn</div>
                                                    <div class="person-title">HOD/EL</div>
                                                    <details>
                                                        <summary>Email Address:</summary>chong_foong_harn@moe.edu.sg
                                                    </details>
                                                </div>
                                                <div class="person">
                                                    <div class="person-name">Mr Pang Tiangui Desmond</div>
                                                    <div class="person-title">Staff Developer</div>
                                                    <details>
                                                        <summary>Email Address:</summary>
                                                    </details>
                                                </div>
                                                <div class="person">
                                                    <div class="person-name">Mdm Chen Huijun</div>
                                                    <div class="person-title">HOD/Hum</div>
                                                    <details>
                                                        <summary>Email Address:</summary>chen_huijun@moe.edu.sg
                                                    </details>
                                                </div>
                                                <div class="person">
                                                    <div class="person-name">Mr Goh Chye Peng David</div>
                                                    <div class="person-title">HOD/Student Mgmt</div>
                                                    <details>
                                                        <summary>Email Address:</summary>goh_chye_peng_david@moe.edu.sg
                                                    </details>
                                                </div>
                                                <div class="person">
                                                    <div class="person-name">Ms Goy Yap Ching</div>
                                                    <div class="person-title">HOD/MTL</div>
                                                    <details>
                                                        <summary>Email Address:</summary>goy_yap_ching@moe.edu.sg
                                                    </details>
                                                </div>
                                                <div class="person">
                                                    <div class="person-name">Mr Chin Pin Chuen Brandon</div>
                                                    <div class="person-title">HOD/ICT</div>
                                                    <details>
                                                        <summary>Email Address:</summary>chin_pin_chuen_brandon@moe.edu.sg
                                                    </details>
                                                </div>
                                                <div class="person">
                                                    <div class="person-name">Mdm Goh Shwu Jun</div>
                                                    <div class="person-title">HOD/Math</div>
                                                    <details>
                                                        <summary>Email Address:</summary>goh_shwu_jun@moe.edu.sg
                                                    </details>
                                                </div>
                                                <div class="person">
                                                    <div class="person-name">Ms Heng Siew Hoon Irene</div>
                                                    <div class="person-title">HOD PE &amp; CCA</div>
                                                    <details>
                                                        <summary>Email Address:</summary>heng_siew_hoon@moe.edu.sg
                                                    </details>
                                                </div>
                                                <div class="person">
                                                    <div class="person-name">Ms Hoon Siew Hui</div>
                                                    <div class="person-title">HOD/Design &amp; Enterprise</div>
                                                    <details>
                                                        <summary>Email Address:</summary>hoon_siew_hui@moe.edu.sg
                                                    </details>
                                                </div>
                                                <div class="person">
                                                    <div class="person-name">Mr Mok Boon Foong</div>
                                                    <div class="person-title">Year Head (US)</div>
                                                    <details>
                                                        <summary>Email Address:</summary>
                                                    </details>
                                                </div>
                                                <div class="person">
                                                    <div class="person-name">Ms Cho Ling Ling Kelly</div>
                                                    <div class="person-title">Year Head (LS)</div>
                                                    <details>
                                                        <summary>Email Address:</summary>
                                                    </details>
                                                </div>
                                                <div class="person">
                                                    <div class="person-name">Ms Per Ching Yee</div>
                                                    <div class="person-title">Administration Manager</div>
                                                    <details>
                                                        <summary>Email Address:</summary>
                                                    </details>
                                                </div>
                                                <div class="person">
                                                    <div class="person-name">Mr Gan Hui Kok Martin</div>
                                                    <div class="person-title">Operations Manager</div>
                                                    <details>
                                                        <summary>Email Address:</summary>
                                                    </details>
                                                </div>
                                                <div class="person">
                                                    <div class="person-name">Ms Sin Puay San</div>
                                                    <div class="person-title"></div>
                                                    <details>
                                                        <summary>Email Address:</summary>
                                                    </details>
                                                </div>
                                                <div class="person">
                                                    <div class="person-name">Mr Kenny</div>
                                                    <div class="person-title">Operations Manager</div>
                                                    <details>
                                                        <summary>Email Address:</summary>
                                                    </details>
                                                </div>
                                                <div class="person">
                                                    <div class="person-name">Ms Vidya Premapadmanabhan</div>
                                                    <div class="person-title">LH/EL</div>
                                                    <details>
                                                        <summary>Email Address:</summary>
                                                    </details>
                                                </div>
                                                <div class="person">
                                                    <div class="person-name">Mr Chen Weiguo Jeremy</div>
                                                    <div class="person-title">LH/Science</div>
                                                    <details>
                                                        <summary>Email Address:</summary>chen_weiguo_jeremy@moe.edu.sg
                                                    </details>
                                                </div>
                                                <div class="person">
                                                    <div class="person-name">Ms Lim Beiyi Michelle</div>
                                                    <div class="person-title">LH/Math &amp; Student Well-Being</div>
                                                    <details>
                                                        <summary>Email Address:</summary>lim_beiyi_michelle@moe.edu.sg
                                                    </details>
                                                </div>
                                                <div class="person">
                                                    <div class="person-name">Mr Wong Mingwei</div>
                                                    <div class="person-title">SH/Student Leadership</div>
                                                    <details>
                                                        <summary>Email Address:</summary>wong_mingwei@moe.edu.sg
                                                    </details>
                                                </div>
                                                <div class="person">
                                                    <div class="person-name">Ms Nurul Ain Bte Kamaldin</div>
                                                    <div class="person-title">SH/PE &amp; CCA</div>
                                                    <details>
                                                        <summary>Email Address:</summary>nurul_ain_kamaldin@moe.edu.sg
                                                    </details>
                                                </div>
                                                <div class="person">
                                                    <div class="person-name">Mdm Alvina Loganathan</div>
                                                    <div class="person-title">SH-CCE</div>
                                                    <details>
                                                        <summary>Email Address:</summary>
                                                    </details>
                                                </div>
                                                <div class="person">
                                                    <div class="person-name">Mdm Ng Hui Yin</div>
                                                    <div class="person-title">SH/Discipline</div>
                                                    <details>
                                                        <summary>Email Address:</summary>ng_hui_yin@moe.edu.sg
                                                    </details>
                                                </div>
                                            </div>
                                            <div class="section-title" id="Teaching-Staff">Teaching Staff</div>
                                            <div class="teaching-staff-section">
                                                <div class="department">
                                                    <div class="department-name">Design and Enterprise Department</div>
                                                    <div class="people-grid">
                                                        <div class="person">
                                                            <div class="person-name">Mr Michael William Cartwright</div>
                                                            <div class="person-title">Music</div>
                                                            <details>
                                                                <summary>Email Address:</summary>michael_william_cartwright@moe.edu.sg
                                                            </details>
                                                        </div>
                                                        <div class="person">
                                                            <div class="person-name">Mr Tan Bock Leong Christopher Jimmy</div>
                                                            <div class="person-title">Art</div>
                                                            <details>
                                                                <summary>Email Address:</summary>tan_bock_leong_christopher@moe.edu.sg
                                                            </details>
                                                        </div>
                                                        <div class="person">
                                                            <div class="person-name">Mr Tham Hwi Jin Darren</div>
                                                            <div class="person-title">Art</div>
                                                            <details>
                                                                <summary>Email Address:</summary>tham_hwi_jin_darren@moe.edu.sg
                                                            </details>
                                                        </div>
                                                        <div class="person">
                                                            <div class="person-name">Mr Yip Seng Yiam</div>
                                                            <div class="person-title">Art</div>
                                                            <details>
                                                                <summary>Email Address:</summary>yip_seng_yiam@moe.edu.sg
                                                            </details>
                                                        </div>
                                                        <div class="person">
                                                            <div class="person-name">Mrs Adele Nair</div>
                                                            <div class="person-title">NFS</div>
                                                            <details>
                                                                <summary>Email Address:</summary>adele_louise_williams@moe.edu.sg
                                                            </details>
                                                        </div>
                                                        <div class="person">
                                                            <div class="person-name">Mr Wee Soh Ye Patrick</div>
                                                            <div class="person-title">D&amp;T</div>
                                                            <details>
                                                                <summary>Email Address:</summary>wee_soh_ye_patrick@moe.edu.sg
                                                            </details>
                                                        </div>
                                                        <div class="person">
                                                            <div class="person-name">Mdm Sutinah Bte Sujaair</div>
                                                            <div class="person-title">NFS</div>
                                                            <details>
                                                                <summary>Email Address:</summary>sutinah_sujaair@moe.edu.sg
                                                            </details>
                                                        </div>
                                                        <div class="person">
                                                            <div class="person-name">Ms Lim Li Whey</div>
                                                            <div class="person-title">NFS</div>
                                                            <details>
                                                                <summary>Email Address:</summary>lim_li_whey@moe.edu.sg
                                                            </details>
                                                        </div>
                                                        <div class="person">
                                                            <div class="person-name">Mr Albert Ong</div>
                                                            <div class="person-title">D&amp;T</div>
                                                            <details>
                                                                <summary>Email Address:</summary>ong_tiong_guan_albert@moe.edu.sg
                                                            </details>
                                                        </div>
                                                        <div class="person">
                                                            <div class="person-name">Mr Lim Chee Wee</div>
                                                            <div class="person-title">D&amp;T</div>
                                                            <details>
                                                                <summary>Email Address:</summary>lim_chee_wee@moe.edu.sg
                                                            </details>
                                                        </div>
                                                        <div class="person">
                                                            <div class="person-name">Mdm Liu Xue Fang</div>
                                                            <div class="person-title">D&amp;T</div>
                                                            <details>
                                                                <summary>Email Address:</summary>liu_xuefang@moe.edu.sg
                                                            </details>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div class="department">
                                                    <div class="department-name">Humanities Department</div>
                                                    <div class="people-grid">
                                                        <div class="person">
                                                            <div class="person-name">Mdm Ng Wan Hwee Doreen</div>
                                                            <div class="person-title">ST/Hist</div>
                                                            <details>
                                                                <summary>Email Address:</summary>ng_wan_hwee_doreen@moe.edu.sg
                                                            </details>
                                                        </div>
                                                        <div class="person">
                                                            <div class="person-name">Mdm Nirmala Devi S Tasiveran</div>
                                                            <div class="person-title">ST/SS</div>
                                                            <details>
                                                                <summary>Email Address:</summary>nirmala_devi_s_tasiveran@moe.edu.sg
                                                            </details>
                                                        </div>
                                                        <div class="person">
                                                            <div class="person-name">Ms Tew Tjin Lian Amelia</div>
                                                            <div class="person-title">SS</div>
                                                            <details>
                                                                <summary>Email Address:</summary>tew_tjin_lian_amelia@moe.edu.sg
                                                            </details>
                                                        </div>
                                                        <div class="person">
                                                            <div class="person-name">Ms Lau Jie Rui Jezreel</div>
                                                            <div class="person-title">Geog</div>
                                                            <details>
                                                                <summary>Email Address:</summary>lau_jie_rui_jezreel@moe.edu.sg
                                                            </details>
                                                        </div>
                                                        <div class="person">
                                                            <div class="person-name">Ms Rohini D/O Ayavoo</div>
                                                            <div class="person-title">Geog</div>
                                                            <details>
                                                                <summary>Email Address:</summary>rohini_ayavoo@moe.edu.sg
                                                            </details>
                                                        </div>
                                                        <div class="person">
                                                            <div class="person-name">Mdm Chua Sock Huang</div>
                                                            <div class="person-title">SS Teacher</div>
                                                            <details>
                                                                <summary>Email Address:</summary>chua_sock_huang@moe.edu.sg
                                                            </details>
                                                        </div>
                                                    </div>
                                                </div></div></div></div>