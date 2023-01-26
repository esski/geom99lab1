# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
https://maps.googleapis.com/maps/api/directions/json?origin=place_id%3AChIJq6p6ZumM1YkRwlenRs5y5SY&destination=side_of_road%3Aplace_id%3AChIJeYCQww0tK4gRaZ8viEl-How&avoid=highways&waypoints=optimize%3Atrue%7Cplace_id%3AChIJNbE3s0Z71YkRfhdD_Ty-1gU%7Cplace_id%3AChIJm8QJ_U151YkRe4dn9TrwUPs%7Cplace_id%3AChIJh8DdB1TUKogRGNOYtlmo8yQ&departure_time=1687622400&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE
```

## Next paste the full JSON response to this query here:

```JSON
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJq6p6ZumM1YkRwlenRs5y5SY",
         "types" : [ "establishment", "point_of_interest", "university" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJm8QJ_U151YkRe4dn9TrwUPs",
         "types" : [ "establishment", "park", "point_of_interest", "tourist_attraction" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJNbE3s0Z71YkRfhdD_Ty-1gU",
         "types" : [ "establishment", "point_of_interest" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJh8DdB1TUKogRGNOYtlmo8yQ",
         "types" : [ "establishment", "park", "point_of_interest", "tourist_attraction" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJeYCQww0tK4gRaZ8viEl-How",
         "types" : [ "establishment", "point_of_interest" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 44.363881,
               "lng" : -78.7309563
            },
            "southwest" : {
               "lat" : 43.7796224,
               "lng" : -79.43540209999999
            }
         },
         "copyrights" : "Map data ©2023 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "3.6 km",
                  "value" : 3551
               },
               "duration" : {
                  "text" : "8 mins",
                  "value" : 464
               },
               "end_address" : "Rivera Park, 83 St Paul St, Lindsay, ON K9V 1S7, Canada",
               "end_location" : {
                  "lat" : 44.3630338,
                  "lng" : -78.736834
               },
               "start_address" : "200 Albert St S, Lindsay, ON K9V 5E6, Canada",
               "start_location" : {
                  "lat" : 44.3410364,
                  "lng" : -78.7416585
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "41 m",
                        "value" : 41
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 8
                     },
                     "end_location" : {
                        "lat" : 44.34126,
                        "lng" : -78.7420679
                     },
                     "html_instructions" : "Head \u003cb\u003enorthwest\u003c/b\u003e toward \u003cb\u003eAlbert St S\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ojsmGjfr_Nk@pA"
                     },
                     "start_location" : {
                        "lat" : 44.3410364,
                        "lng" : -78.7416585
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "20 m",
                        "value" : 20
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 9
                     },
                     "end_location" : {
                        "lat" : 44.3414172,
                        "lng" : -78.7419474
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eAlbert St S\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{ksmG|hr_N_@W"
                     },
                     "start_location" : {
                        "lat" : 44.34126,
                        "lng" : -78.7420679
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 461
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 108
                     },
                     "end_location" : {
                        "lat" : 44.3445376,
                        "lng" : -78.7408128
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eAlbert St S\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{lsmGdhr_NBK@MAOE[SsAUyAEQEQM[MWQWsAc@ICWESAODQD{Bx@eA`@mC~@MF"
                     },
                     "start_location" : {
                        "lat" : 44.3414172,
                        "lng" : -78.7419474
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 833
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 71
                     },
                     "end_location" : {
                        "lat" : 44.3469849,
                        "lng" : -78.7309563
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eMary St W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eKawartha Lakes County Rd 19\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "k`tmG`ar_Nk@qAK[Ww@YeB_@iCYkCWsAo@qEIo@_BoL{@kGu@mFKo@S_B"
                     },
                     "start_location" : {
                        "lat" : 44.3445376,
                        "lng" : -78.7408128
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.8 km",
                        "value" : 1809
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 202
                     },
                     "end_location" : {
                        "lat" : 44.3617678,
                        "lng" : -78.7348616
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eLindsay St S\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "sotmGncp_NeBh@cA\\kDlAeA^mDjAaA\\A@k@R]LmFhBeBl@sC~@kFhBgFfB[Lc@Nk@R}@\\]J{@\\}@Zg@P}Aj@u@XwFtBc@LcA\\A?a@HE@]AUCSGE?o@[AASIKCGASEG?K?U@S@OCQGUUKQGWGe@AIa@cE"
                     },
                     "start_location" : {
                        "lat" : 44.3469849,
                        "lng" : -78.7309563
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 248
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 25
                     },
                     "end_location" : {
                        "lat" : 44.363881,
                        "lng" : -78.73587549999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eSt Paul St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "alwmGz{p_NsBv@iDpAgC`A"
                     },
                     "start_location" : {
                        "lat" : 44.3617678,
                        "lng" : -78.7348616
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 110
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 30
                     },
                     "end_location" : {
                        "lat" : 44.3632942,
                        "lng" : -78.73684109999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "gywmGfbq_NJl@Ll@BL@B@@@@B@l@VNFB@BB@B@F?@BV"
                     },
                     "start_location" : {
                        "lat" : 44.363881,
                        "lng" : -78.73587549999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "29 m",
                        "value" : 29
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 11
                     },
                     "end_location" : {
                        "lat" : 44.3630338,
                        "lng" : -78.736834
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the left\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "quwmGfhq_Nr@A"
                     },
                     "start_location" : {
                        "lat" : 44.3632942,
                        "lng" : -78.73684109999999
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "3.4 km",
                  "value" : 3418
               },
               "duration" : {
                  "text" : "6 mins",
                  "value" : 383
               },
               "end_address" : "Lindsay, Kawartha Lakes, ON K9V 6K2, Canada",
               "end_location" : {
                  "lat" : 44.3547051,
                  "lng" : -78.7613585
               },
               "start_address" : "Rivera Park, 83 St Paul St, Lindsay, ON K9V 1S7, Canada",
               "start_location" : {
                  "lat" : 44.3630338,
                  "lng" : -78.736834
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "29 m",
                        "value" : 29
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 7
                     },
                     "end_location" : {
                        "lat" : 44.3632942,
                        "lng" : -78.73684109999999
                     },
                     "html_instructions" : "Head \u003cb\u003enorth\u003c/b\u003e",
                     "polyline" : {
                        "points" : "}swmGdhq_Ns@@"
                     },
                     "start_location" : {
                        "lat" : 44.3630338,
                        "lng" : -78.736834
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 110
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 23
                     },
                     "end_location" : {
                        "lat" : 44.363881,
                        "lng" : -78.73587549999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eSt Paul St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "quwmGfhq_NCW?AAGACCCCAOGm@WCAAAAAACCMMm@Km@"
                     },
                     "start_location" : {
                        "lat" : 44.3632942,
                        "lng" : -78.73684109999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 248
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 33
                     },
                     "end_location" : {
                        "lat" : 44.3617678,
                        "lng" : -78.7348616
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eSt Paul St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gywmGfbq_NfCaAhDqArBw@"
                     },
                     "start_location" : {
                        "lat" : 44.363881,
                        "lng" : -78.73587549999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 528
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 55
                     },
                     "end_location" : {
                        "lat" : 44.3579478,
                        "lng" : -78.7358969
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e at the 1st cross street onto \u003cb\u003eColborne St E\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eLindsay St N\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Lindsay St N\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "alwmGz{p_N`@bE@HFd@FVJPTTPFNBRATAJ?F?RDF@JBRH@@n@ZD?RFTB\\@DA`@I@?bA]b@MvFuB"
                     },
                     "start_location" : {
                        "lat" : 44.3617678,
                        "lng" : -78.7348616
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 189
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 30
                     },
                     "end_location" : {
                        "lat" : 44.3575205,
                        "lng" : -78.7381766
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eWellington St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "etvmGjbq_NA^AP@N@NFZJn@Hn@TzADTBTVpB"
                     },
                     "start_location" : {
                        "lat" : 44.3579478,
                        "lng" : -78.7358969
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 369
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 37
                     },
                     "end_location" : {
                        "lat" : 44.3606781,
                        "lng" : -78.73960409999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eWilliam St N\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "oqvmGrpq_NqFjBKD_Ct@eBl@sCdA"
                     },
                     "start_location" : {
                        "lat" : 44.3575205,
                        "lng" : -78.7381766
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.8 km",
                        "value" : 1849
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 188
                     },
                     "end_location" : {
                        "lat" : 44.3555271,
                        "lng" : -78.7617175
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eColborne St W\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "gewmGnyq_Nh@lDdA|G`AhHBXdAdHl@~Dz@`GdBjLv@dF@PDXLp@l@fEl@~DPnABNPfBRrAVzAV~Aj@~DHn@f@lDT~Ap@~ET~AJn@t@nFHn@DXTvA"
                     },
                     "start_location" : {
                        "lat" : 44.3606781,
                        "lng" : -78.73960409999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 96
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 10
                     },
                     "end_location" : {
                        "lat" : 44.3547051,
                        "lng" : -78.7613585
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eSt Joseph Rd\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "aevmGvcv_N`@OZK\\OHCTIJENEJA"
                     },
                     "start_location" : {
                        "lat" : 44.3555271,
                        "lng" : -78.7617175
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "87.8 km",
                  "value" : 87752
               },
               "duration" : {
                  "text" : "1 hour 13 mins",
                  "value" : 4391
               },
               "end_address" : "Lake Wilcox Park, 55 Olde Bayview Ave, Richmond Hill, ON L4E 3C8, Canada",
               "end_location" : {
                  "lat" : 43.9523687,
                  "lng" : -79.4313616
               },
               "start_address" : "Lindsay, Kawartha Lakes, ON K9V 6K2, Canada",
               "start_location" : {
                  "lat" : 44.3547051,
                  "lng" : -78.7613585
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 96
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 9
                     },
                     "end_location" : {
                        "lat" : 44.3555271,
                        "lng" : -78.7617175
                     },
                     "html_instructions" : "Head \u003cb\u003enorth\u003c/b\u003e on \u003cb\u003eSt Joseph Rd\u003c/b\u003e toward \u003cb\u003eColborne St W\u003c/b\u003e",
                     "polyline" : {
                        "points" : "}_vmGnav_NK@ODKDUHIB]N[Ja@N"
                     },
                     "start_location" : {
                        "lat" : 44.3547051,
                        "lng" : -78.7613585
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.1 km",
                        "value" : 2074
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 150
                     },
                     "end_location" : {
                        "lat" : 44.3495903,
                        "lng" : -78.7864431
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eColborne St W\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "aevmGvcv_NpBxNZtBp@pErBxNJn@b@bDLt@`@tCXdBn@|D@DFf@Jn@Jn@`@nCx@lFJn@T|AJn@Hn@l@|Dl@xDBPF\\V|AJn@Jn@Jl@fA|Gn@zDbBjKF^l@|DHn@nAlI"
                     },
                     "start_location" : {
                        "lat" : 44.3555271,
                        "lng" : -78.7617175
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 103
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 14
                     },
                     "end_location" : {
                        "lat" : 44.348679,
                        "lng" : -78.78619309999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eMonarch Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "}_umGf~z_NnB]dAS"
                     },
                     "start_location" : {
                        "lat" : 44.3495903,
                        "lng" : -78.7864431
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "23.9 km",
                        "value" : 23920
                     },
                     "duration" : {
                        "text" : "17 mins",
                        "value" : 1038
                     },
                     "end_location" : {
                        "lat" : 44.2882161,
                        "lng" : -79.073256
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eHwy 7\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eTrans-Canada Hwy\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gztmGt|z_NCbACfA?DA`AAlB@hAB~@@p@FtAF`AFx@B\\D^NxABRDXdAvHv@`GVrBDTX|BH|@JjAF|@Bl@Bn@Bv@@ZBrA?xA?^Az@?f@Cv@C~@AXATEp@IjAI~@KnAi@nG[zDCf@AXIxAEjA?bD?nABlA?BF|A@\\Fv@Bh@Df@@NJ`ANjATbBF`@Jn@Jn@`@pC^nCHj@Hn@Hp@?@Jj@Ff@J|@Hz@D`@@LB`@@NDp@FhABz@@p@@H@f@@v@DpC@VBvCD~B@`B?T@ZHlG@\\?x@B~@BdABz@@HDn@Bn@NjBBXD^D^Fd@VnB`@pCJn@|@hG`BfLt@lF@BHj@t@nFt@nFd@`DlB|Mt@nFt@nFlAnI^lCHh@l@dEn@fERtAt@nFHj@VbBT~AHn@NdADXJn@Hn@Jl@Jn@Lz@hArHRjAh@lDb@lCDZb@nCN|@Fd@TdBTdBDZ|@bHr@tFpAtJX|BXpBHn@l@vEDVR~AT`BFb@Jz@f@~Dt@bGl@`FXlBp@tEb@~CZtBd@hDb@jDBRh@~DT~AXvB~@hHL~@VpBRxAfB~MDZLdA\\pCb@bD`@hDLfAn@rEHn@Hn@r@`FZtBfD`VBPZvBBJ|@jGPlAHn@`@nCjAnIHn@XlB\\~BHn@vC~ST~AT~ANbAp@xE@H\\dCDTDXbB~LZ~BPjAh@bEBNHp@`@|CZ`CVhBd@vD@DFh@h@`E\\lCJn@ZbC`@|CJt@VjBd@rDRxAR~AF`@b@hDThBn@zEVnBJz@Jn@VtB@FHn@RvA@FHn@@HVvBZdCPtAPrAFd@VjBHh@?Dj@dEd@nDhAxIvAnKFf@Jn@PrAp@jFT|Af@vDr@nFj@fEj@pE^pCR|ARrAJz@Lx@ZvBTlB@BHj@\\nCJn@Hn@T~AHn@^nCHn@Hn@T~AHn@Lz@Fb@NjABRR`BFd@@Ht@rFHj@\\nCHn@Hf@Jv@~@dHFj@f@vDLv@\\nCJn@Hn@Hn@T~AHn@j@fEHn@Jn@PpAT~An@vEb@dDDXJn@D^^jCJr@BLXrBNz@@N\\vB\\dCXhB?DBNp@~E@F@Fh@nD@NxA|JF^@Nh@nDBLHn@f@nDN~@rAlJBNh@nD@N\\~BBN~A|KBNF^T~AHn@`@lCBNHn@RnAL~@Jn@j@~Dn@hEnBrMHj@F^`@nC~@hGDZ?BPfANdANdARpANhANz@F`@XnBBLPjAJj@Hh@XjBVhBPjADXHn@L|@RtAJn@\\hC~@~FPrAFVT~AH`@TlBN`AJn@PfA?@Lv@DPBP@BFb@\\tA`@zAZ`A@DRh@P`@@DLXFNTf@Rf@@BTb@R`@@BTf@Tf@JRb@`APf@Zz@Z|@Rp@HVFTJf@d@pBPdATxAT|AJx@Jl@Jn@Ff@Jl@@HPhABTT~AFd@@Hf@tD@HHn@Z~Bf@jD\\bCT~At@lF^nC`A~GHj@@BT~AT~AHh@^rCTzAJr@Hn@TzA`AbH^nCV`Bd@hD|@dFh@jDDZ@FXjBLv@\\vBp@jD`@hB`@dB@DLf@H`@Nn@Nv@Px@H`@Jn@@D\\pBLz@Lz@VlBNtAPzAXpCXpCv@xHNvA@NTxBFl@`@xDTtB@HFd@Df@Jv@RtA@HT~ALdAHj@`@nCT|AT~ABT^pCl@hE\\hCtA|JZtBj@lE`@~CVfBRvA~@~GhAnIZvBt@vFVpBHn@Z~BR~AVpBT|AHn@Hp@R~A~@~Gd@pDb@dD\\`Cp@~EhAnIHn@T~AHn@Fd@@HJp@Fb@@JFb@@JFb@Jp@@HPtA@H`@xCXnBDVDZRzAR`BHf@D\\BNHl@F`@@JJr@Hp@^nC\\jCJr@R~AJn@R~AJn@VnBR~AT~ATdBJv@d@`D"
                     },
                     "start_location" : {
                        "lat" : 44.348679,
                        "lng" : -78.78619309999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.9 km",
                        "value" : 2860
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 158
                     },
                     "end_location" : {
                        "lat" : 44.2636574,
                        "lng" : -79.06262559999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eHwy 7\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-12 S\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-7\u003c/b\u003e (signs for \u003cb\u003eToronto\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eWhitby\u003c/b\u003e)",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "k`imGz~raNpBs@fBw@^Mz@YFAJETIJCbA]VIzFiBTIJEx@W`@MpBq@fIiCDCjA_@tFiBlC}@l@Q`@ODA|@[\\KDA`@Od@Q\\KtAe@dEuA`A]`Bi@xAi@LEFA|@[`@OjBm@LGLEdA]BANGn@S@APGp@U^MTILE`@M?ARGz@YzAg@hEwAVI|@[NG@?TIJC`A]@?XKNEt@WxDqAn@Ud@O~HmCHC~Ai@DARIvC_AXKDATGTIBAj@OFCn@Kl@G"
                     },
                     "start_location" : {
                        "lat" : 44.2882161,
                        "lng" : -79.073256
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "5.6 km",
                        "value" : 5644
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 294
                     },
                     "end_location" : {
                        "lat" : 44.2485005,
                        "lng" : -79.130259
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eRiver St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eDurham Regional Rd 10\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Durham Regional Rd 10\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{fdmGl|paNL`AJ`AD\\Hp@DZb@~CJv@^pCVrBFVjAjIn@dENjAJn@Fb@d@nDn@tE@Bt@hFn@`F`@tCr@nFBTDXn@tED\\pBtO~BlPXtBHr@Jn@r@nFVnBr@hFPtAT`B@FFd@Hn@Jn@@HFd@T~A@HFd@@HRtAJn@Hn@jApIDVd@bDBTDXHn@Jn@R~AJn@Hn@Jn@Hn@h@~DDTDXjAlITvAxA|JlAlIJl@LbA\\~BFj@Jn@\\pCR~AHn@LdALz@Jx@Hd@Hn@lAxIh@tDJn@@F?BDV@HT~A@Hh@tD@FRvAJn@T|ATbBBRFZBPj@~DD\\BPD\\DPD\\BPJn@D\\BPHn@FZBRBL@LBPJn@D\\BP@FHf@D\\BPPlALt@@JHn@RrA@JHb@Jx@RrA@JT~AHb@@JD\\BPJn@Hn@@FFf@BLD`@L|@r@nFF`@R~AFf@Lv@Jz@Fb@Hn@BJHn@Fb@@JVpBZ|BHb@@JFb@@JFd@BHHn@Fb@@JJn@ZbCBJFb@l@jEPrA"
                     },
                     "start_location" : {
                        "lat" : 44.2636574,
                        "lng" : -79.06262559999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "12.5 km",
                        "value" : 12454
                     },
                     "duration" : {
                        "text" : "9 mins",
                        "value" : 533
                     },
                     "end_location" : {
                        "lat" : 44.1398003,
                        "lng" : -79.1037992
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eLake Ridge Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eDurham Regional Rd 23\u003c/b\u003e (signs for \u003cb\u003eRegional Rd 23\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eUxbridge\u003c/b\u003e)",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "chamGbc~aNvC}@`F}AxC}@`@OlA_@XIfBi@lEsA`@MfBi@@?bA[`@MZKDAb@Mx@WHC`@O`@OHCVIb@O`@OFAXK`@M`@Mb@M`@O`@M`@Mb@MJElAa@NE\\Kb@Mp@UDAJE`@Mb@M\\KBAn@Ml@M@AHA`@GBAx@GHArAMjBMpCUFAVAb@EfAGjBOb@CPANAb@Eb@Cb@EjBMt@EPApF_@bBMr@Gb@CFAH?vAKb@ERAr@Gb@CRAr@Gb@CPA|@IdCORANALATCb@CPAPAb@ETAJARANCb@Cb@CBAfCQB?RANAP?PAj@AbB?P@|Gj@b@DhBN@?b@DdAHF@ZBb@Db@Db@BZD`BLB?\\DnC\\B?^B`AFB?ZBF@fAHZBF@b@D~@JbCRPBb@Bb@Dr@Ft@HfAHP@PBP@PBt@FdADR@tEPP@hFRb@BpCJdACh@Gn@IbCk@bA[`@MxFeBXKbA[`@MHC|Ae@fBk@bA[`@MJCx@W`@Mt@ULEb@Or@UNE`@Mb@M`@MPGNE`@M`@MdA]`@MvAc@jA]FCb@M`@MZKDC`@M`@MZKFA`@M`@MZKDAb@M`@MZK~Ag@p@S`@MRGrAc@`@Mb@MvBq@xDmAfA]b@OdPeFJETGpAc@TGtDkAVIdA]JETGbA[|FkBzAe@l@Qv@Wn@Sv@W|FiBTItBo@tAc@nEyABA`A[TIrBs@@?lIoCl@S`@Ob@M^MrAc@bBi@TITIhBk@HC?ATG@AHCTGt@U~Ag@VKB?DCbCy@|Ae@DCDA`@M\\MDAxC_ANGlC{@`Bi@DAZK`@MHCRGb@IREDAf@In@Gt@CVAp@?v@B\\Bj@HVBlAV~Cr@rCl@nAXb@JNBPDlB^vBd@tBb@B@b@HvAZNB@@fB\\JB@@v@PdAT@@`@Hl@Ld@JRD^FB?`@F@@n@FH@J@X@H@b@@D?\\?J?B?RAH?XALATCPAPCXEHAVEHCHAXG\\IBAzAe@JCJEVG`@MdAYHEVGPGNEdBg@pAa@VIFAlCs@hB_@b@INEt@O`@Gb@Ib@IBA\\IdASb@INCRERELCjB_@`AU@AdAYPE@?n@Sb@M`@MpAa@@?LGb@MPENGPGNEFCHCNEb@MPGNGPENGLEhA[`@MZKx@W`@MPENG\\KDAr@UNE`@MRI^K~@[pBm@nA_@PGXIHCbBi@@A@?bA]r@UNG`@Mb@O`@MdBm@dEuAlBm@@AdCy@@?RIl@S~@[d@O^M@?h@Q`A]\\Mv@WpAa@n@Sp@U~Ai@hA_@"
                     },
                     "start_location" : {
                        "lat" : 44.2485005,
                        "lng" : -79.130259
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "4.3 km",
                        "value" : 4314
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 244
                     },
                     "end_location" : {
                        "lat" : 44.12806,
                        "lng" : -79.1553237
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eDavis Dr\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "w`llGv}xaN`@lCVhBV|AFd@DXDTf@fDPlADXPlAPpAHh@?BL|@@DNbAD\\VfBNhAXjBJv@RxAT|A@FPrA?BLv@Fd@BLFh@Hf@?FLx@Z|B@FFf@DXXrBJn@?DDRBNHt@Hd@D\\DZHh@XjBVlBDXFd@Lz@R|ABNVlBTbBLz@RtADZPlAHh@?Bf@lDL`AFb@Lz@VlBPnAD\\`@rCRxABPHp@Hf@TbB?@Hn@Jn@?DRtA?BJn@Hj@?BJl@BVDXHl@NfAHf@F^BND^BLHp@\\`C^jCL|@@@Hl@T`BHl@@@h@zD?@PhABRDZDRd@jDBP^dC@H@HRtA@FFf@BNJn@Z|BBNF^BND^BNF^Hn@Jn@BRHn@T|AFZFh@Jt@Hf@T~AJn@?D^hCJn@?DJn@T|AFh@@DJn@Hn@RvALv@Ff@@DJn@LbAXnBLz@j@|DRvA@F^lCBNF^@HFd@DXNdA@JHb@?Bh@xD@B`@rCRvAt@lF@F`CrP"
                     },
                     "start_location" : {
                        "lat" : 44.1398003,
                        "lng" : -79.1037992
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.8 km",
                        "value" : 2782
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 154
                     },
                     "end_location" : {
                        "lat" : 44.1041613,
                        "lng" : -79.14499979999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eConcession Rd 6\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "kwilGv_cbNn@SpDkAPE^MTIxAe@|@YfBi@LCHCpAc@^MdBk@@A`A[b@O`@M`@MfBm@bA]TGhC{@p@U`Bg@@?^Mb@O`@M`@M@?^Mb@O`@M@?^M@A^K`@MRGNG`@MJEDANE`@O`@MlE{ARGd@OpBq@FC@Ax@WdA]`@MlEyA`@MjDiAfBk@tHcCxAg@~@YtAe@bA[jDiAtGyB|@YjAa@XK`@MfGuB`@Oj@Oh@UB?\\Od@S\\O"
                     },
                     "start_location" : {
                        "lat" : 44.12806,
                        "lng" : -79.1553237
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.1 km",
                        "value" : 2051
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 128
                     },
                     "end_location" : {
                        "lat" : 44.0866,
                        "lng" : -79.1374235
                     },
                     "html_instructions" : "At the roundabout, continue straight to stay on \u003cb\u003eConcession Rd 6\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "_belGf_abN@@?@@@?@@@@?@@?@@?@@@?@?B?B?@A@?@AB?@A@?@A@A@??A@??A@??A?A@A?A?A?A@ARIn@UjA]^Ot@WHCr@UJEl@SXIJE^K\\MTINEvBs@PEzCaA@A\\K@?`@O@?^M`@O`@MBA^MJETG`@O`@M@?fBm@^M@?^M@AVIBABAfBi@B?`A[@?FCx@WHC@?xAg@JEx@Y`@M\\Md@Q`@MVKHCjDkAVKtDoAVKrDoA|Ai@jDiARILEjDiARGhC{@vDoAb@OpC_A"
                     },
                     "start_location" : {
                        "lat" : 44.1041613,
                        "lng" : -79.14499979999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "13.0 km",
                        "value" : 12979
                     },
                     "duration" : {
                        "text" : "10 mins",
                        "value" : 627
                     },
                     "end_location" : {
                        "lat" : 44.0140246,
                        "lng" : -79.23816599999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eDurham Regional Hwy 47\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gtalGzo_bN\\rABRJd@HZXdBXbBrAjJRvA`A|GJn@t@lFT|A~@~GHn@fCnRb@`DJp@LfA^zCb@pCdAbId@`D@HPfADXThBBTRtA@JN`ADR^hBRt@J\\DNJZ@BXr@\\r@HPNTZj@b@h@f@h@b@f@d@d@lAv@j@X`@LPFj@Nv@NZDz@F^?~@CZCz@K~@UvAc@xCaAhC{@fCw@|Ag@VIxAg@vAc@NGp@UDC`@MHEFAJEd@Qh@QZKb@OJEJEHC`@Ox@YhAa@ZKPGNGdBo@\\K`@MtCcAv@WJEpAc@xAg@hAa@RIfDiAJEhC{@hDmALEf@QZKzBw@fBm@xAe@rBq@FCzAg@DArAe@DCd@MZK|@UJCFAVEp@I`@CP?X?V?n@DXBJBl@N`@N~DvA^Hp@RD@`Bj@j@Vn@\\n@f@d@f@RTRTh@t@n@lAZr@\\~@Tz@Ln@DTRfAh@`D@Jh@rDzAjKF^l@|DF`@XjB|@dG`AvHT`BRnARpANdAL|@VtARdA?@R|@\\pAXdABHHPX|@d@tAbA~BBBpAtCfA~BjAdCjBbEt@~An@xAbAzBxBxEBBpFrLdBvDl@rA\\r@dA~BP^x@dBP^HRz@hBrBpEt@~AnAlCbEbJBDrAvCr@zALZTd@nD|HbAxBh@jAtBzEhC|Ff@fAdB|D^x@n@xA\\t@JVj@nAl@nARd@\\r@t@|At@zA`@|@Xn@Zr@`@z@b@`A\\v@BDJVFNDJJPHTTd@FLLXFLHRNZTh@`@z@FN`@|@`@|@\\r@Tf@^v@Zt@P\\HPXp@N\\DH|BdF~@vB`AvBbAzBP`@LVvA|CFNl@nAzCvGR`@lC~FLTNXFNxA~CTh@tCrGLVLZFLdBlEtBfFtAlDFN|@vBbA`Cz@lBl@zATf@N\\`BlD`@z@DJbArBjE|InBbEx@`BjAhCvDfINX`AtBJVjAfClDzHjBbE?@jAfCfCnFzCrGjFbLp@|AP\\xAfD"
                     },
                     "start_location" : {
                        "lat" : 44.0866,
                        "lng" : -79.1374235
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "4.3 km",
                        "value" : 4331
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 229
                     },
                     "end_location" : {
                        "lat" : 44.000974,
                        "lng" : -79.28872609999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eBloomington Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eYork Regional Rd 40\u003c/b\u003e",
                     "polyline" : {
                        "points" : "snskGpesbNhB`EJVrAzCnBvDLVhAdCh@hAt@dBBD^`AXt@BD@Ft@pB~@fDf@rBt@`EVjBN`Az@vGvAlKRtAl@rEd@dDVnBn@pEf@pDHn@T~A?BBHdAbIHj@h@~DZ`CJ~@BNHz@H|@@JNzBB\\@XV|CDb@?@NhBFd@DZDd@VrBLfAR~ATfBJv@ZfC^jCD\\DXlEv\\jBnNFb@h@|D@JFf@Jl@PrApDhXh@zDhAlHx@fFBRXlBPhAFZJp@N`AJn@@hAHd@d@vCp@fE"
                     },
                     "start_location" : {
                        "lat" : 44.0140246,
                        "lng" : -79.23816599999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 359
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 25
                     },
                     "end_location" : {
                        "lat" : 44.0000594,
                        "lng" : -79.2928915
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e2nd\u003c/b\u003e exit and stay on \u003cb\u003eBloomington Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eYork Regional Rd 40\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "a}pkGpa}bNCBCBCDADADADAD?F?D?D?D?F@D@D@D@BHJD@p@jE?D@BXhBt@zEJh@Lv@RtA"
                     },
                     "start_location" : {
                        "lat" : 44.000974,
                        "lng" : -79.28872609999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "11.9 km",
                        "value" : 11943
                     },
                     "duration" : {
                        "text" : "10 mins",
                        "value" : 626
                     },
                     "end_location" : {
                        "lat" : 43.96796399999999,
                        "lng" : -79.43522589999999
                     },
                     "html_instructions" : "Continue straight to stay on \u003cb\u003eBloomington Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eYork Regional Rd 40\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "kwpkGp{}bN@JHb@FVJZf@vD@F^nChB~MD`@j@hE@@Hl@?@h@|DR~AFb@@JDRbDlVf@xDJr@fAhIr@fFp@hEBPFz@Fd@NfAf@dDVbBJp@Jn@XfBXtBPfAFh@N^Jz@VhBXvBtBzOXrBvC~TL~@n@pEBRn@dFv@bG@HBVdAdIh@vDD^VnBz@lGj@lEv@fGJz@RbBBl@RhBl@lFd@dEf@dER~Ah@rDVpBJ\\\\nCvApLd@~DPxAf@fElApI\\fCdA|GHn@RpABJZvBv@lFhB`MHn@`AvGXjBFd@DRTzAZvBBV`@nCFl@@\\PjBR`BVzB@FDj@\\vC@VVnCNvAZpCNlAJr@BPNl@p@`Fr@vE`@vC`BtK`AvGn@pEBHXnBV`Br@xEZzBzAzJz@|F`AvGJt@^~BL~AXjB`AlGZnBl@xDl@~D`@dCDVAT@LDZRtAZvBpAzIRpAfAfH`@nCJl@`@nCBVBNBNJn@D\\@H@BF`@V|AFd@XdBp@vEN~@XpBHb@|@vG^lC\\hBV~AXfB|CtPJd@vAtHl@zCLt@Jl@b@hCDXBD@BFFXlBd@xCPfAVzA`@tCXnBXpBb@tCPjANfAXlBDVR`B^nCbBrMJz@Fh@RxA@JFb@\\nC?DHh@Hn@\\nCHn@f@~DP~ABLD`@R~ABL\\pCNnAHn@R~AHn@R~AL~@r@xFBTDVrAtKbCxRf@`ETjBx@fGT~A"
                     },
                     "start_location" : {
                        "lat" : 44.0000594,
                        "lng" : -79.2928915
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.6 km",
                        "value" : 1583
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 103
                     },
                     "end_location" : {
                        "lat" : 43.9540662,
                        "lng" : -79.43200019999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eBayview Ave\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "wnjkGduycNB`@nF_AhBUPCPE|@[jFy@ZEv@M|Cc@zCc@lAOz@Kn@IFAxCc@JCxBUh@Gh@Ij@I`C[bBUbAONCzBY@?zEo@vB[|@M`@Ch@CLCZIXGn@Wj@[FG"
                     },
                     "start_location" : {
                        "lat" : 43.96796399999999,
                        "lng" : -79.43522589999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "46 m",
                        "value" : 46
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 7
                     },
                     "end_location" : {
                        "lat" : 43.95386329999999,
                        "lng" : -79.43250549999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eN Lake Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}wgkG~`ycNNb@HXNf@"
                     },
                     "start_location" : {
                        "lat" : 43.9540662,
                        "lng" : -79.43200019999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 213
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 52
                     },
                     "end_location" : {
                        "lat" : 43.9523687,
                        "lng" : -79.4313616
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eOlde Bayview Ave\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "svgkGddycNdBUPCdAMJADADADAFEHG@ADGFIFMFMFODQFQBc@@_@"
                     },
                     "start_location" : {
                        "lat" : 43.95386329999999,
                        "lng" : -79.43250549999999
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "21.5 km",
                  "value" : 21525
               },
               "duration" : {
                  "text" : "32 mins",
                  "value" : 1929
               },
               "end_address" : "5600 Yonge St, North York, ON M2N 5S2, Canada",
               "end_location" : {
                  "lat" : 43.7796224,
                  "lng" : -79.41560539999999
               },
               "start_address" : "Lake Wilcox Park, 55 Olde Bayview Ave, Richmond Hill, ON L4E 3C8, Canada",
               "start_location" : {
                  "lat" : 43.9523687,
                  "lng" : -79.4313616
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 213
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 60
                     },
                     "end_location" : {
                        "lat" : 43.95386329999999,
                        "lng" : -79.43250549999999
                     },
                     "html_instructions" : "Head \u003cb\u003ewest\u003c/b\u003e on \u003cb\u003eOlde Bayview Ave\u003c/b\u003e toward \u003cb\u003eLakeside Crescent\u003c/b\u003e",
                     "polyline" : {
                        "points" : "imgkG~|xcNA^Cb@GPEPGNGLGLGHEFA@IFGDE@E@E@K@eALQBeBT"
                     },
                     "start_location" : {
                        "lat" : 43.9523687,
                        "lng" : -79.4313616
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "46 m",
                        "value" : 46
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 10
                     },
                     "end_location" : {
                        "lat" : 43.9540662,
                        "lng" : -79.43200019999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eN Lake Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "svgkGddycNOg@IYOc@"
                     },
                     "start_location" : {
                        "lat" : 43.95386329999999,
                        "lng" : -79.43250549999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "19.3 km",
                        "value" : 19281
                     },
                     "duration" : {
                        "text" : "27 mins",
                        "value" : 1603
                     },
                     "end_location" : {
                        "lat" : 43.7849905,
                        "lng" : -79.39221549999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e at the 1st cross street onto \u003cb\u003eBayview Ave\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}wgkG~`ycNp@i@n@o@TYT]Xc@@AbCkFLWpA{B`AkAVY`@]@CRMPKRIHCNG`@IH?f@OfA[jBg@h@Qv@W`@Kl@Oh@Kr@Mx@Ij@EVAPAb@@@?TB~FhAlDt@zBd@fB\\`D~@NDhFdA|D~@b@F@?nDz@zA^f@?n@LxAZrAZ~Bh@B@`BZB@XFd@Bd@@`@AF?^Cd@E`AKZE@Ad@K^K@A^Mp@YvBcA\\E`Aa@n@WNG\\Kj@MhASZETCb@Eb@Eb@GfAM~@KVIhBUn@IVE~B]d@Ir@KbCYx@KBANK^E`Dg@B?d@ItB[\\Ej@Kt@Kb@GZGb@GdAQb@Gb@GdAQ`BWpB[ZE~AWHAfAQdAOb@GZG\\E`@Gb@E~@M`H}@`@GtEm@`BSfEg@NCvEm@hC]f@IxAUNChBYlCc@xCe@hBY`C_@~AUjAQt@KfCa@pASjB[b@GxAUbFy@XGVE`AQr@Kl@Kl@IfBWdBYh@K`BU`BWtE{@dAUlCe@z@Op@MHCdDm@f@I@?b@IhBWv@M|Fy@\\E^?LAfBQp@Kn@M^G@?r@Mn@IbC[rAQz@Ob@ONO~B_@hBYbAQdAQDAdAQdCa@@?^Gn@Kx@MfBY`@G~AWf@I|@OtB]hDi@b@Ir@Kv@MtCa@nIqAZGzB]bGaA\\GTFdASdAM`BYbBYLC|Dm@dBUTCZEb@IZEh@ERCLAh@GRElASv@M^IFABCPO^GLCFAx@Mx@MtB]hEo@b@GRElDi@d@GNCnAQn@Mv@Md@GdBYz@KnAQ~AYdCa@vCe@jAQ|@MTENCTC`@GFCLAFA`@G`@GFAp@Kb@GjASZEDAdAOVD`AQ`AO`@GTEVEPCVCdBYVCtB[`@GPCTEPErAW@?\\?tDs@^GpB[dBSFARENCTCzAW\\Gn@GXSNCb@IRCPFVEREXCb@G|@Q|B]b@GnB[\\G~Dm@F?LCtBYdASlASZEd@I`Fw@XELCn@IjCa@bAO|BWjEs@|AWrAUlB_@`BWjDg@~GuAREPCPChEs@|@K`@GLCd@IfAUNCPEb@Ib@Ir@M~@O`Cc@BAREPEB?TEdAOb@G`@GXEvDo@hIuAXEzE{@r@ObC]z@Mf@IfAQf@I\\GtB_@rAQ|@QdASrCg@n@MpCi@hBUfBYhEu@r@Kp@KdAQNARE@?`@G\\GZE`@Ib@GfAO`@GpASrAUp@MxAU^EPUREnB]rCa@f@G~AS~@QHAp@IZDF?bAOPCr@GHADCd@Yb@Ij@INChBWn@Id@KVEVC|Cc@jEq@d@GhAOf@FB?D?`Fo@bAQREFCd@YLEd@IzB]vASrAUzAUh@IpDm@XEjASx@MnCc@PCtAU|@OjASjB[RENEb@OVKJGDCJD@?@?@?@?DCLILIFEDEJGNMPQ`@a@`@a@DGTUNOJILMr@i@PIPKLGRINGVKNEBADAREd@INCBANCNAJCVEf@G`@Ib@GbAOD?hEo@f@Gd@GlASZGx@Kn@KREPC~@MzCe@lASF?HCFA`BUTGpAOLCbBUbAOd@GrAQlAO`De@j@GvAUFAREFAl@Ef@EJMLAvASn@Gp@Ix@K\\ENCDAPALC`@E~ASl@GVEtAOzAQFAXEr@Kd@EDADAFANADADAHAVEZAPA@AfAK\\D\\En@IJAXERCR?@?zAQ"
                     },
                     "start_location" : {
                        "lat" : 43.9540662,
                        "lng" : -79.43200019999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.0 km",
                        "value" : 1956
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 235
                     },
                     "end_location" : {
                        "lat" : 43.7797832,
                        "lng" : -79.41546919999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eFinch Ave E\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ewfjGjhqcNR`AJh@@BJf@FRDT?@BL@F@HFb@NhAF^Z`CN`AHn@Hl@RvAHl@DTVpBF`@f@zDVbBHp@VpBx@dGFf@F\\PxAJn@Hn@PxADZ~@hHVhB`@zCHf@PpABNJn@^rCD^b@zCNdABZHh@TbBR|AB^F\\PlALz@Fb@BTPrABXDZD\\BVDTPxAH\\NfAJb@@LJj@@H@HL|@@JFb@Nj@@PLdABf@BPVfB"
                     },
                     "start_location" : {
                        "lat" : 43.7849905,
                        "lng" : -79.39221549999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "29 m",
                        "value" : 29
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 21
                     },
                     "end_location" : {
                        "lat" : 43.7796224,
                        "lng" : -79.41560539999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eYonge St\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "svejGtyucND`@XE"
                     },
                     "start_location" : {
                        "lat" : 43.7797832,
                        "lng" : -79.41546919999999
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "ojsmGjfr_Nk@pA_@WDYq@yEg@wAgCeAqDbAsE`By@iA}AcIkBaN}Ey]S_BeBh@oFjBwHjC}KxDoXlJuSrHgAH_Bg@gBUkA_@[oAc@mE}GhCgC`AJl@Pz@HHdAd@Fd@r@As@@CYKQcAc@UaAKm@fCaA|GiCj@rFz@fAtBJxCr@jCu@vFuBA^?`@^jCv@xFcNtEsCdAh@lDfCfQrD`WdD|T|DpX~El]zApKdBo@|@W}@VeBn@rHzh@rDpVjDjUbDrSbFd[v@lFnAlInB]dASCbAClA@xHv@nLpEd^X|LoCle@XbPxAjLdD|Yp@re@l@pKhHvg@`TvzApWfkBrb@|aDt\\|bClRpyAnm@lsEtk@~}DpHzg@pAbH|B~GbHdQ~E~ZdLjy@hMxy@hGf]vGhn@d^hlCdMf_A`D~UjA|Id@`DpBs@fCeAdBk@bJuChSuGzd@qObOcFns@}UpCg@h@rEpFb`@hRbvAzOvjA~UhdBvRrvAjEn[PrAvC}@zJ{ChCy@dOqE|L}D`OuElRqBf]_Cp`@mCfOn@`Ip@pRbB|ZvBpLd@bHaAfQoFjR_GhQqFnkA}^l_AmZ`XuIvFq@rDPxK|BtNzCzH`BfLdBbGc@bQcFvSkErOcEl]oKnr@iUpLbz@zUvdBhXlmBpF``@`CrPn@SbEqAlEwAzKmDrUsHtIqC`uAid@rCs@xx@eXxl@eSpC_A\\rANx@|@dFjIll@nMn`ArBtHbEbG`EdCpCl@vD?lJgChQyFfEyA`SaHde@_PxJcDhFo@|KnCdExAxCbChClEfA`EbGt`@tFp`@dCnKfc@jaAtZvp@xh@`kAvd@fcAtZ|s@jg@pfAnf@teA~@dCrEnQzHrk@fIdp@~E|c@bWfkBlDfZbBjKtJbq@vNvfAhPhkAlb@teDrLly@lGhj@de@~`DlFf^pPz`AdM`|@bFna@hO|lAX`CxIuAlI_BnQcCjg@wGlBYzAs@VZX`AvBY|ASv@_AXwA@_@A^Kt@]|@YZcFt@YaA`@mAtBkCdFaK|BgCfDiAbMcDnCSzHnAn_@lIrSjExFj@lFw@fK_E~X}Dvt@yKd}@aMtf@wHjg@uIrPuBhFs@bEaAfQsCxMuBvt@}KzUiDtH{AdRsCj]kFhQcCz[}EdGkAbEa@xc@aHvu@yL~~@wO|d@wHnKaB|D_A~HmAtI_ArHwA~QmCrGg@dCu@rSeD`PiCdGwAjHgGtFuAzz@{L`_@yEtEYhBUT?zAQR`ALl@Rz@Jl@`BxLhHri@|Hbl@zCzTx@fFVpCv@bC"
         },
         "summary" : "Lindsay St S",
         "warnings" : [],
         "waypoint_order" : [ 1, 0, 2 ]
      }
   ],
   "status" : "OK"
}
```
____
## Rubric

This is part of your first practical lab in Week 3 

1. A working URL properly documented in the MarkDown with a unique origin and destination earns 50%
2. Including one to four additional functioning unique parameters from the API earns 50-70%
3. Having 3 or more functioning unique/novel and well-thought out parameters from the API earns 70-90%
4. Including more than 2 "stops", including links to display PlaceIDs on Google Maps, or other innovative presentations earns 80%-100%. 
