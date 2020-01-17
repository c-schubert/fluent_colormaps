# Additional Colormaps for ANSYS Fluent
Just copy and paste the scheme code(s) to ANSYS Fluent console. Colormaps will be available and saved within the case and can be used as any other includes colormap.


## Viridis
![viridis](./img/viridis.png "viridis colormap")

```scheme
(cxsetvar 'cmap-list (cons '("viridis" (256 (0.000000 0.267004 0.004874 0.329415) (0.003922 0.268510 0.009605 0.335427) (0.007843 0.269944 0.014625 0.341379) (0.011765 0.271305 0.019942 0.347269) (0.015686 0.272594 0.025563 0.353093) (0.019608 0.273809 0.031497 0.358853) (0.023529 0.274952 0.037752 0.364543) (0.027451 0.276022 0.044167 0.370164) (0.031373 0.277018 0.050344 0.375715) (0.035294 0.277941 0.056324 0.381191) (0.039216 0.278791 0.062145 0.386592) (0.043137 0.279566 0.067836 0.391917) (0.047059 0.280267 0.073417 0.397163) (0.050980 0.280894 0.078907 0.402329) (0.054902 0.281446 0.084320 0.407414) (0.058824 0.281924 0.089666 0.412415) (0.062745 0.282327 0.094955 0.417331) (0.066667 0.282656 0.100196 0.422160) (0.070588 0.282910 0.105393 0.426902) (0.074510 0.283091 0.110553 0.431554) (0.078431 0.283197 0.115680 0.436115) (0.082353 0.283229 0.120777 0.440584) (0.086275 0.283187 0.125848 0.444960) (0.090196 0.283072 0.130895 0.449241) (0.094118 0.282884 0.135920 0.453427) (0.098039 0.282623 0.140926 0.457517) (0.101961 0.282290 0.145912 0.461510) (0.105882 0.281887 0.150881 0.465405) (0.109804 0.281412 0.155834 0.469201) (0.113725 0.280868 0.160771 0.472899) (0.117647 0.280255 0.165693 0.476498) (0.121569 0.279574 0.170599 0.479997) (0.125490 0.278826 0.175490 0.483397) (0.129412 0.278012 0.180367 0.486697) (0.133333 0.277134 0.185228 0.489898) (0.137255 0.276194 0.190074 0.493001) (0.141176 0.275191 0.194905 0.496005) (0.145098 0.274128 0.199721 0.498911) (0.149020 0.273006 0.204520 0.501721) (0.152941 0.271828 0.209303 0.504434) (0.156863 0.270595 0.214069 0.507052) (0.160784 0.269308 0.218818 0.509577) (0.164706 0.267968 0.223549 0.512008) (0.168627 0.266580 0.228262 0.514349) (0.172549 0.265145 0.232956 0.516599) (0.176471 0.263663 0.237631 0.518762) (0.180392 0.262138 0.242286 0.520837) (0.184314 0.260571 0.246922 0.522828) (0.188235 0.258965 0.251537 0.524736) (0.192157 0.257322 0.256130 0.526563) (0.196078 0.255645 0.260703 0.528312) (0.200000 0.253935 0.265254 0.529983) (0.203922 0.252194 0.269783 0.531579) (0.207843 0.250425 0.274290 0.533103) (0.211765 0.248629 0.278775 0.534556) (0.215686 0.246811 0.283237 0.535941) (0.219608 0.244972 0.287675 0.537260) (0.223529 0.243113 0.292092 0.538516) (0.227451 0.241237 0.296485 0.539709) (0.231373 0.239346 0.300855 0.540844) (0.235294 0.237441 0.305202 0.541921) (0.239216 0.235526 0.309527 0.542944) (0.243137 0.233603 0.313828 0.543914) (0.247059 0.231674 0.318106 0.544834) (0.250980 0.229739 0.322361 0.545706) (0.254902 0.227802 0.326594 0.546532) (0.258824 0.225863 0.330805 0.547314) (0.262745 0.223925 0.334994 0.548053) (0.266667 0.221989 0.339161 0.548752) (0.270588 0.220057 0.343307 0.549413) (0.274510 0.218130 0.347432 0.550038) (0.278431 0.216210 0.351535 0.550627) (0.282353 0.214298 0.355619 0.551184) (0.286275 0.212395 0.359683 0.551710) (0.290196 0.210503 0.363727 0.552206) (0.294118 0.208623 0.367752 0.552675) (0.298039 0.206756 0.371758 0.553117) (0.301961 0.204903 0.375746 0.553533) (0.305882 0.203063 0.379716 0.553925) (0.309804 0.201239 0.383670 0.554294) (0.313725 0.199430 0.387607 0.554642) (0.317647 0.197636 0.391528 0.554969) (0.321569 0.195860 0.395433 0.555276) (0.325490 0.194100 0.399323 0.555565) (0.329412 0.192357 0.403199 0.555836) (0.333333 0.190631 0.407061 0.556089) (0.337255 0.188923 0.410910 0.556326) (0.341176 0.187231 0.414746 0.556547) (0.345098 0.185556 0.418570 0.556753) (0.349020 0.183898 0.422383 0.556944) (0.352941 0.182256 0.426184 0.557120) (0.356863 0.180629 0.429975 0.557282) (0.360784 0.179019 0.433756 0.557430) (0.364706 0.177423 0.437527 0.557565) (0.368627 0.175841 0.441290 0.557685) (0.372549 0.174274 0.445044 0.557792) (0.376471 0.172719 0.448791 0.557885) (0.380392 0.171176 0.452530 0.557965) (0.384314 0.169646 0.456262 0.558030) (0.388235 0.168126 0.459988 0.558082) (0.392157 0.166617 0.463708 0.558119) (0.396078 0.165117 0.467423 0.558141) (0.400000 0.163625 0.471133 0.558148) (0.403922 0.162142 0.474838 0.558140) (0.407843 0.160665 0.478540 0.558115) (0.411765 0.159194 0.482237 0.558073) (0.415686 0.157729 0.485932 0.558013) (0.419608 0.156270 0.489624 0.557936) (0.423529 0.154815 0.493313 0.557840) (0.427451 0.153364 0.497000 0.557724) (0.431373 0.151918 0.500685 0.557587) (0.435294 0.150476 0.504369 0.557430) (0.439216 0.149039 0.508051 0.557250) (0.443137 0.147607 0.511733 0.557049) (0.447059 0.146180 0.515413 0.556823) (0.450980 0.144759 0.519093 0.556572) (0.454902 0.143343 0.522773 0.556295) (0.458824 0.141935 0.526453 0.555991) (0.462745 0.140536 0.530132 0.555659) (0.466667 0.139147 0.533812 0.555298) (0.470588 0.137770 0.537492 0.554906) (0.474510 0.136408 0.541173 0.554483) (0.478431 0.135066 0.544853 0.554029) (0.482353 0.133743 0.548535 0.553541) (0.486275 0.132444 0.552216 0.553018) (0.490196 0.131172 0.555899 0.552459) (0.494118 0.129933 0.559582 0.551864) (0.498039 0.128729 0.563265 0.551229) (0.501961 0.127568 0.566949 0.550556) (0.505882 0.126453 0.570633 0.549841) (0.509804 0.125394 0.574318 0.549086) (0.513725 0.124395 0.578002 0.548287) (0.517647 0.123463 0.581687 0.547445) (0.521569 0.122606 0.585371 0.546557) (0.525490 0.121831 0.589055 0.545623) (0.529412 0.121148 0.592739 0.544641) (0.533333 0.120565 0.596422 0.543611) (0.537255 0.120092 0.600104 0.542530) (0.541176 0.119738 0.603785 0.541400) (0.545098 0.119512 0.607464 0.540218) (0.549020 0.119423 0.611141 0.538982) (0.552941 0.119483 0.614817 0.537692) (0.556863 0.119699 0.618490 0.536347) (0.560784 0.120081 0.622161 0.534946) (0.564706 0.120638 0.625828 0.533488) (0.568627 0.121380 0.629492 0.531973) (0.572549 0.122312 0.633153 0.530398) (0.576471 0.123444 0.636809 0.528763) (0.580392 0.124780 0.640461 0.527068) (0.584314 0.126326 0.644107 0.525311) (0.588235 0.128087 0.647749 0.523491) (0.592157 0.130067 0.651384 0.521608) (0.596078 0.132268 0.655014 0.519661) (0.600000 0.134692 0.658636 0.517649) (0.603922 0.137339 0.662252 0.515571) (0.607843 0.140210 0.665859 0.513427) (0.611765 0.143303 0.669459 0.511215) (0.615686 0.146616 0.673050 0.508936) (0.619608 0.150148 0.676631 0.506589) (0.623529 0.153894 0.680203 0.504172) (0.627451 0.157851 0.683765 0.501686) (0.631373 0.162016 0.687316 0.499129) (0.635294 0.166383 0.690856 0.496502) (0.639216 0.170948 0.694384 0.493803) (0.643137 0.175707 0.697900 0.491033) (0.647059 0.180653 0.701402 0.488189) (0.650980 0.185783 0.704891 0.485273) (0.654902 0.191090 0.708366 0.482284) (0.658824 0.196571 0.711827 0.479221) (0.662745 0.202219 0.715272 0.476084) (0.666667 0.208030 0.718701 0.472873) (0.670588 0.214000 0.722114 0.469588) (0.674510 0.220124 0.725509 0.466226) (0.678431 0.226397 0.728888 0.462789) (0.682353 0.232815 0.732247 0.459277) (0.686275 0.239374 0.735588 0.455688) (0.690196 0.246070 0.738910 0.452024) (0.694118 0.252899 0.742211 0.448284) (0.698039 0.259857 0.745492 0.444467) (0.701961 0.266941 0.748751 0.440573) (0.705882 0.274149 0.751988 0.436601) (0.709804 0.281477 0.755203 0.432552) (0.713725 0.288921 0.758394 0.428426) (0.717647 0.296479 0.761561 0.424223) (0.721569 0.304148 0.764704 0.419943) (0.725490 0.311925 0.767822 0.415586) (0.729412 0.319809 0.770914 0.411152) (0.733333 0.327796 0.773980 0.406640) (0.737255 0.335885 0.777018 0.402049) (0.741176 0.344074 0.780029 0.397381) (0.745098 0.352360 0.783011 0.392636) (0.749020 0.360741 0.785964 0.387814) (0.752941 0.369214 0.788888 0.382914) (0.756863 0.377779 0.791781 0.377939) (0.760784 0.386433 0.794644 0.372886) (0.764706 0.395174 0.797475 0.367757) (0.768627 0.404001 0.800275 0.362552) (0.772549 0.412913 0.803041 0.357269) (0.776471 0.421908 0.805774 0.351910) (0.780392 0.430983 0.808473 0.346476) (0.784314 0.440137 0.811138 0.340967) (0.788235 0.449368 0.813768 0.335384) (0.792157 0.458674 0.816363 0.329727) (0.796078 0.468053 0.818921 0.323998) (0.800000 0.477504 0.821444 0.318195) (0.803922 0.487026 0.823929 0.312321) (0.807843 0.496615 0.826376 0.306377) (0.811765 0.506271 0.828786 0.300362) (0.815686 0.515992 0.831158 0.294279) (0.819608 0.525776 0.833491 0.288127) (0.823529 0.535621 0.835785 0.281908) (0.827451 0.545524 0.838039 0.275626) (0.831373 0.555484 0.840254 0.269281) (0.835294 0.565498 0.842430 0.262877) (0.839216 0.575563 0.844566 0.256415) (0.843137 0.585678 0.846661 0.249897) (0.847059 0.595839 0.848717 0.243329) (0.850980 0.606045 0.850733 0.236712) (0.854902 0.616293 0.852709 0.230052) (0.858824 0.626579 0.854645 0.223353) (0.862745 0.636902 0.856542 0.216620) (0.866667 0.647257 0.858400 0.209861) (0.870588 0.657642 0.860219 0.203082) (0.874510 0.668054 0.861999 0.196293) (0.878431 0.678489 0.863742 0.189503) (0.882353 0.688944 0.865448 0.182725) (0.886275 0.699415 0.867117 0.175971) (0.890196 0.709898 0.868751 0.169257) (0.894118 0.720391 0.870350 0.162603) (0.898039 0.730889 0.871916 0.156029) (0.901961 0.741388 0.873449 0.149561) (0.905882 0.751884 0.874951 0.143228) (0.909804 0.762373 0.876424 0.137064) (0.913725 0.772852 0.877868 0.131109) (0.917647 0.783315 0.879285 0.125405) (0.921569 0.793760 0.880678 0.120005) (0.925490 0.804182 0.882046 0.114965) (0.929412 0.814576 0.883393 0.110347) (0.933333 0.824940 0.884720 0.106217) (0.937255 0.835270 0.886029 0.102646) (0.941176 0.845561 0.887322 0.099702) (0.945098 0.855810 0.888601 0.097452) (0.949020 0.866013 0.889868 0.095953) (0.952941 0.876168 0.891125 0.095250) (0.956863 0.886271 0.892374 0.095374) (0.960784 0.896320 0.893616 0.096335) (0.964706 0.906311 0.894855 0.098125) (0.968627 0.916242 0.896091 0.100717) (0.972549 0.926106 0.897330 0.104071) (0.976471 0.935904 0.898570 0.108131) (0.980392 0.945636 0.899815 0.112838) (0.984314 0.955300 0.901065 0.118128) (0.988235 0.964894 0.902323 0.123941) (0.992157 0.974417 0.903590 0.130215) (0.996078 0.983868 0.904867 0.136897) (1.000000 0.993248 0.906157 0.143936)) )(cxgetvar 'cmap-list)))
```


## Inferno
![inferno](./img/inferno.png "inferno colormap")
``` scheme
(cxsetvar 'cmap-list (cons '("inferno" (256 (0.000000 0.001462 0.000466 0.013866) (0.003922 0.002267 0.001270 0.018570) (0.007843 0.003299 0.002249 0.024239) (0.011765 0.004547 0.003392 0.030909) (0.015686 0.006006 0.004692 0.038558) (0.019608 0.007676 0.006136 0.046836) (0.023529 0.009561 0.007713 0.055143) (0.027451 0.011663 0.009417 0.063460) (0.031373 0.013995 0.011225 0.071862) (0.035294 0.016561 0.013136 0.080282) (0.039216 0.019373 0.015133 0.088767) (0.043137 0.022447 0.017199 0.097327) (0.047059 0.025793 0.019331 0.105930) (0.050980 0.029432 0.021503 0.114621) (0.054902 0.033385 0.023702 0.123397) (0.058824 0.037668 0.025921 0.132232) (0.062745 0.042253 0.028139 0.141141) (0.066667 0.046915 0.030324 0.150164) (0.070588 0.051644 0.032474 0.159254) (0.074510 0.056449 0.034569 0.168414) (0.078431 0.061340 0.036590 0.177642) (0.082353 0.066331 0.038504 0.186962) (0.086275 0.071429 0.040294 0.196354) (0.090196 0.076637 0.041905 0.205799) (0.094118 0.081962 0.043328 0.215289) (0.098039 0.087411 0.044556 0.224813) (0.101961 0.092990 0.045583 0.234358) (0.105882 0.098702 0.046402 0.243904) (0.109804 0.104551 0.047008 0.253430) (0.113725 0.110536 0.047399 0.262912) (0.117647 0.116656 0.047574 0.272321) (0.121569 0.122908 0.047536 0.281624) (0.125490 0.129285 0.047293 0.290788) (0.129412 0.135778 0.046856 0.299776) (0.133333 0.142378 0.046242 0.308553) (0.137255 0.149073 0.045468 0.317085) (0.141176 0.155850 0.044559 0.325338) (0.145098 0.162689 0.043554 0.333277) (0.149020 0.169575 0.042489 0.340874) (0.152941 0.176493 0.041402 0.348111) (0.156863 0.183429 0.040329 0.354971) (0.160784 0.190367 0.039309 0.361447) (0.164706 0.197297 0.038400 0.367535) (0.168627 0.204209 0.037632 0.373238) (0.172549 0.211095 0.037030 0.378563) (0.176471 0.217949 0.036615 0.383522) (0.180392 0.224763 0.036405 0.388129) (0.184314 0.231538 0.036405 0.392400) (0.188235 0.238273 0.036621 0.396353) (0.192157 0.244967 0.037055 0.400007) (0.196078 0.251620 0.037705 0.403378) (0.200000 0.258234 0.038571 0.406485) (0.203922 0.264810 0.039647 0.409345) (0.207843 0.271347 0.040922 0.411976) (0.211765 0.277850 0.042353 0.414392) (0.215686 0.284321 0.043933 0.416608) (0.219608 0.290763 0.045644 0.418637) (0.223529 0.297178 0.047470 0.420491) (0.227451 0.303568 0.049396 0.422182) (0.231373 0.309935 0.051407 0.423721) (0.235294 0.316282 0.053490 0.425116) (0.239216 0.322610 0.055634 0.426377) (0.243137 0.328921 0.057827 0.427511) (0.247059 0.335217 0.060060 0.428524) (0.250980 0.341500 0.062325 0.429425) (0.254902 0.347771 0.064616 0.430217) (0.258824 0.354032 0.066925 0.430906) (0.262745 0.360284 0.069247 0.431497) (0.266667 0.366529 0.071579 0.431994) (0.270588 0.372768 0.073915 0.432400) (0.274510 0.379001 0.076253 0.432719) (0.278431 0.385228 0.078591 0.432955) (0.282353 0.391453 0.080927 0.433109) (0.286275 0.397674 0.083257 0.433183) (0.290196 0.403894 0.085580 0.433179) (0.294118 0.410113 0.087896 0.433098) (0.298039 0.416331 0.090203 0.432943) (0.301961 0.422549 0.092501 0.432714) (0.305882 0.428768 0.094790 0.432412) (0.309804 0.434987 0.097069 0.432039) (0.313725 0.441207 0.099338 0.431594) (0.317647 0.447428 0.101597 0.431080) (0.321569 0.453651 0.103848 0.430498) (0.325490 0.459875 0.106089 0.429846) (0.329412 0.466100 0.108322 0.429125) (0.333333 0.472328 0.110547 0.428334) (0.337255 0.478558 0.112764 0.427475) (0.341176 0.484789 0.114974 0.426548) (0.345098 0.491022 0.117179 0.425552) (0.349020 0.497257 0.119379 0.424488) (0.352941 0.503493 0.121575 0.423356) (0.356863 0.509730 0.123769 0.422156) (0.360784 0.515967 0.125960 0.420887) (0.364706 0.522206 0.128150 0.419549) (0.368627 0.528444 0.130341 0.418142) (0.372549 0.534683 0.132534 0.416667) (0.376471 0.540920 0.134729 0.415123) (0.380392 0.547157 0.136929 0.413511) (0.384314 0.553392 0.139134 0.411829) (0.388235 0.559624 0.141346 0.410078) (0.392157 0.565854 0.143567 0.408258) (0.396078 0.572081 0.145797 0.406369) (0.400000 0.578304 0.148039 0.404411) (0.403922 0.584521 0.150294 0.402385) (0.407843 0.590734 0.152563 0.400290) (0.411765 0.596940 0.154848 0.398125) (0.415686 0.603139 0.157151 0.395891) (0.419608 0.609330 0.159474 0.393589) (0.423529 0.615513 0.161817 0.391219) (0.427451 0.621685 0.164184 0.388781) (0.431373 0.627847 0.166575 0.386276) (0.435294 0.633998 0.168992 0.383704) (0.439216 0.640135 0.171438 0.381065) (0.443137 0.646260 0.173914 0.378359) (0.447059 0.652369 0.176421 0.375586) (0.450980 0.658463 0.178962 0.372748) (0.454902 0.664540 0.181539 0.369846) (0.458824 0.670599 0.184153 0.366879) (0.462745 0.676638 0.186807 0.363849) (0.466667 0.682656 0.189501 0.360757) (0.470588 0.688653 0.192239 0.357603) (0.474510 0.694627 0.195021 0.354388) (0.478431 0.700576 0.197851 0.351113) (0.482353 0.706500 0.200728 0.347777) (0.486275 0.712396 0.203656 0.344383) (0.490196 0.718264 0.206636 0.340931) (0.494118 0.724103 0.209670 0.337424) (0.498039 0.729909 0.212759 0.333861) (0.501961 0.735683 0.215906 0.330245) (0.505882 0.741423 0.219112 0.326576) (0.509804 0.747127 0.222378 0.322856) (0.513725 0.752794 0.225706 0.319085) (0.517647 0.758422 0.229097 0.315266) (0.521569 0.764010 0.232554 0.311399) (0.525490 0.769556 0.236077 0.307485) (0.529412 0.775059 0.239667 0.303526) (0.533333 0.780517 0.243327 0.299523) (0.537255 0.785929 0.247056 0.295477) (0.541176 0.791293 0.250856 0.291390) (0.545098 0.796607 0.254728 0.287264) (0.549020 0.801871 0.258674 0.283099) (0.552941 0.807082 0.262692 0.278898) (0.556863 0.812239 0.266786 0.274661) (0.560784 0.817341 0.270954 0.270390) (0.564706 0.822386 0.275197 0.266085) (0.568627 0.827372 0.279517 0.261750) (0.572549 0.832299 0.283913 0.257383) (0.576471 0.837165 0.288385 0.252988) (0.580392 0.841969 0.292933 0.248564) (0.584314 0.846709 0.297559 0.244113) (0.588235 0.851384 0.302260 0.239636) (0.592157 0.855992 0.307038 0.235133) (0.596078 0.860533 0.311892 0.230606) (0.600000 0.865006 0.316822 0.226055) (0.603922 0.869409 0.321827 0.221482) (0.607843 0.873741 0.326906 0.216886) (0.611765 0.878001 0.332060 0.212268) (0.615686 0.882188 0.337287 0.207628) (0.619608 0.886302 0.342586 0.202968) (0.623529 0.890341 0.347957 0.198286) (0.627451 0.894305 0.353399 0.193584) (0.631373 0.898192 0.358911 0.188860) (0.635294 0.902003 0.364492 0.184116) (0.639216 0.905735 0.370140 0.179350) (0.643137 0.909390 0.375856 0.174563) (0.647059 0.912966 0.381636 0.169755) (0.650980 0.916462 0.387481 0.164924) (0.654902 0.919879 0.393389 0.160070) (0.658824 0.923215 0.399359 0.155193) (0.662745 0.926470 0.405389 0.150292) (0.666667 0.929644 0.411479 0.145367) (0.670588 0.932737 0.417627 0.140417) (0.674510 0.935747 0.423831 0.135440) (0.678431 0.938675 0.430091 0.130438) (0.682353 0.941521 0.436405 0.125409) (0.686275 0.944285 0.442772 0.120354) (0.690196 0.946965 0.449191 0.115272) (0.694118 0.949562 0.455660 0.110164) (0.698039 0.952075 0.462178 0.105031) (0.701961 0.954506 0.468744 0.099874) (0.705882 0.956852 0.475356 0.094695) (0.709804 0.959114 0.482014 0.089499) (0.713725 0.961293 0.488716 0.084289) (0.717647 0.963387 0.495462 0.079073) (0.721569 0.965397 0.502249 0.073859) (0.725490 0.967322 0.509078 0.068659) (0.729412 0.969163 0.515946 0.063488) (0.733333 0.970919 0.522853 0.058367) (0.737255 0.972590 0.529798 0.053324) (0.741176 0.974176 0.536780 0.048392) (0.745098 0.975677 0.543798 0.043618) (0.749020 0.977092 0.550850 0.039050) (0.752941 0.978422 0.557937 0.034931) (0.756863 0.979666 0.565057 0.031409) (0.760784 0.980824 0.572209 0.028508) (0.764706 0.981895 0.579392 0.026250) (0.768627 0.982881 0.586606 0.024661) (0.772549 0.983779 0.593849 0.023770) (0.776471 0.984591 0.601122 0.023606) (0.780392 0.985315 0.608422 0.024202) (0.784314 0.985952 0.615750 0.025592) (0.788235 0.986502 0.623105 0.027814) (0.792157 0.986964 0.630485 0.030908) (0.796078 0.987337 0.637890 0.034916) (0.800000 0.987622 0.645320 0.039886) (0.803922 0.987819 0.652773 0.045581) (0.807843 0.987926 0.660250 0.051750) (0.811765 0.987945 0.667748 0.058329) (0.815686 0.987874 0.675267 0.065257) (0.819608 0.987714 0.682807 0.072489) (0.823529 0.987464 0.690366 0.079990) (0.827451 0.987124 0.697944 0.087731) (0.831373 0.986694 0.705540 0.095694) (0.835294 0.986175 0.713153 0.103863) (0.839216 0.985566 0.720782 0.112229) (0.843137 0.984865 0.728427 0.120785) (0.847059 0.984075 0.736087 0.129527) (0.850980 0.983196 0.743758 0.138453) (0.854902 0.982228 0.751442 0.147565) (0.858824 0.981173 0.759135 0.156863) (0.862745 0.980032 0.766837 0.166353) (0.866667 0.978806 0.774545 0.176037) (0.870588 0.977497 0.782258 0.185923) (0.874510 0.976108 0.789974 0.196018) (0.878431 0.974638 0.797692 0.206332) (0.882353 0.973088 0.805409 0.216877) (0.886275 0.971468 0.813122 0.227658) (0.890196 0.969783 0.820825 0.238686) (0.894118 0.968041 0.828515 0.249972) (0.898039 0.966243 0.836191 0.261534) (0.901961 0.964394 0.843848 0.273391) (0.905882 0.962517 0.851476 0.285546) (0.909804 0.960626 0.859069 0.298010) (0.913725 0.958720 0.866624 0.310820) (0.917647 0.956834 0.874129 0.323974) (0.921569 0.954997 0.881569 0.337475) (0.925490 0.953215 0.888942 0.351369) (0.929412 0.951546 0.896226 0.365627) (0.933333 0.950018 0.903409 0.380271) (0.937255 0.948683 0.910473 0.395289) (0.941176 0.947594 0.917399 0.410665) (0.945098 0.946809 0.924168 0.426373) (0.949020 0.946392 0.930761 0.442367) (0.952941 0.946403 0.937159 0.458592) (0.956863 0.946903 0.943348 0.474970) (0.960784 0.947937 0.949318 0.491426) (0.964706 0.949545 0.955063 0.507860) (0.968627 0.951740 0.960587 0.524203) (0.972549 0.954529 0.965896 0.540361) (0.976471 0.957896 0.971003 0.556275) (0.980392 0.961812 0.975924 0.571925) (0.984314 0.966249 0.980678 0.587206) (0.988235 0.971162 0.985282 0.602154) (0.992157 0.976511 0.989753 0.616760) (0.996078 0.982257 0.994109 0.631017) (1.000000 0.988362 0.998364 0.644924)) )(cxgetvar 'cmap-list)))
```

## Magma
![magma](./img/magma.png "magma colormap")
```scheme
(cxsetvar 'cmap-list (cons '("magma" (256 (0.000000 0.001462 0.000466 0.013866) (0.003922 0.002258 0.001295 0.018331) (0.007843 0.003279 0.002305 0.023708) (0.011765 0.004512 0.003490 0.029965) (0.015686 0.005950 0.004843 0.037130) (0.019608 0.007588 0.006356 0.044973) (0.023529 0.009426 0.008022 0.052844) (0.027451 0.011465 0.009828 0.060750) (0.031373 0.013708 0.011771 0.068667) (0.035294 0.016156 0.013840 0.076603) (0.039216 0.018815 0.016026 0.084584) (0.043137 0.021692 0.018320 0.092610) (0.047059 0.024792 0.020715 0.100676) (0.050980 0.028123 0.023201 0.108787) (0.054902 0.031696 0.025765 0.116965) (0.058824 0.035520 0.028397 0.125209) (0.062745 0.039608 0.031090 0.133515) (0.066667 0.043830 0.033830 0.141886) (0.070588 0.048062 0.036607 0.150327) (0.074510 0.052320 0.039407 0.158841) (0.078431 0.056615 0.042160 0.167446) (0.082353 0.060949 0.044794 0.176129) (0.086275 0.065330 0.047318 0.184892) (0.090196 0.069764 0.049726 0.193735) (0.094118 0.074257 0.052017 0.202660) (0.098039 0.078815 0.054184 0.211667) (0.101961 0.083446 0.056225 0.220755) (0.105882 0.088155 0.058133 0.229922) (0.109804 0.092949 0.059904 0.239164) (0.113725 0.097833 0.061531 0.248477) (0.117647 0.102815 0.063010 0.257854) (0.121569 0.107899 0.064335 0.267289) (0.125490 0.113094 0.065492 0.276784) (0.129412 0.118405 0.066479 0.286321) (0.133333 0.123833 0.067295 0.295879) (0.137255 0.129380 0.067935 0.305443) (0.141176 0.135053 0.068391 0.315000) (0.145098 0.140858 0.068654 0.324538) (0.149020 0.146785 0.068738 0.334011) (0.152941 0.152839 0.068637 0.343404) (0.156863 0.159018 0.068354 0.352688) (0.160784 0.165308 0.067911 0.361816) (0.164706 0.171713 0.067305 0.370771) (0.168627 0.178212 0.066576 0.379497) (0.172549 0.184801 0.065732 0.387973) (0.176471 0.191460 0.064818 0.396152) (0.180392 0.198177 0.063862 0.404009) (0.184314 0.204935 0.062907 0.411514) (0.188235 0.211718 0.061992 0.418647) (0.192157 0.218512 0.061158 0.425392) (0.196078 0.225302 0.060445 0.431742) (0.200000 0.232077 0.059889 0.437695) (0.203922 0.238826 0.059517 0.443256) (0.207843 0.245543 0.059352 0.448436) (0.211765 0.252220 0.059415 0.453248) (0.215686 0.258857 0.059706 0.457710) (0.219608 0.265447 0.060237 0.461840) (0.223529 0.271994 0.060994 0.465660) (0.227451 0.278493 0.061978 0.469190) (0.231373 0.284951 0.063168 0.472451) (0.235294 0.291366 0.064553 0.475462) (0.239216 0.297740 0.066117 0.478243) (0.243137 0.304081 0.067835 0.480812) (0.247059 0.310382 0.069702 0.483186) (0.250980 0.316654 0.071690 0.485380) (0.254902 0.322899 0.073782 0.487408) (0.258824 0.329114 0.075972 0.489287) (0.262745 0.335308 0.078236 0.491024) (0.266667 0.341482 0.080564 0.492631) (0.270588 0.347636 0.082946 0.494121) (0.274510 0.353773 0.085373 0.495501) (0.278431 0.359898 0.087831 0.496778) (0.282353 0.366012 0.090314 0.497960) (0.286275 0.372116 0.092816 0.499053) (0.290196 0.378211 0.095332 0.500067) (0.294118 0.384299 0.097855 0.501002) (0.298039 0.390384 0.100379 0.501864) (0.301961 0.396467 0.102902 0.502658) (0.305882 0.402548 0.105420 0.503386) (0.309804 0.408629 0.107930 0.504052) (0.313725 0.414709 0.110431 0.504662) (0.317647 0.420791 0.112920 0.505215) (0.321569 0.426877 0.115395 0.505714) (0.325490 0.432967 0.117855 0.506160) (0.329412 0.439062 0.120298 0.506555) (0.333333 0.445163 0.122724 0.506901) (0.337255 0.451271 0.125132 0.507198) (0.341176 0.457386 0.127522 0.507448) (0.345098 0.463508 0.129893 0.507652) (0.349020 0.469640 0.132245 0.507809) (0.352941 0.475780 0.134577 0.507921) (0.356863 0.481929 0.136891 0.507989) (0.360784 0.488088 0.139186 0.508011) (0.364706 0.494258 0.141462 0.507988) (0.368627 0.500438 0.143719 0.507920) (0.372549 0.506629 0.145958 0.507806) (0.376471 0.512831 0.148179 0.507648) (0.380392 0.519045 0.150383 0.507443) (0.384314 0.525270 0.152569 0.507192) (0.388235 0.531507 0.154739 0.506895) (0.392157 0.537755 0.156894 0.506551) (0.396078 0.544015 0.159033 0.506159) (0.400000 0.550287 0.161158 0.505719) (0.403922 0.556571 0.163269 0.505230) (0.407843 0.562866 0.165368 0.504692) (0.411765 0.569172 0.167454 0.504105) (0.415686 0.575490 0.169530 0.503466) (0.419608 0.581819 0.171596 0.502777) (0.423529 0.588158 0.173652 0.502035) (0.427451 0.594508 0.175701 0.501241) (0.431373 0.600868 0.177743 0.500394) (0.435294 0.607238 0.179779 0.499492) (0.439216 0.613617 0.181811 0.498536) (0.443137 0.620005 0.183840 0.497524) (0.447059 0.626401 0.185867 0.496456) (0.450980 0.632805 0.187893 0.495332) (0.454902 0.639216 0.189921 0.494150) (0.458824 0.645633 0.191952 0.492910) (0.462745 0.652056 0.193986 0.491611) (0.466667 0.658483 0.196027 0.490253) (0.470588 0.664915 0.198075 0.488836) (0.474510 0.671349 0.200133 0.487358) (0.478431 0.677786 0.202203 0.485819) (0.482353 0.684224 0.204286 0.484219) (0.486275 0.690661 0.206384 0.482558) (0.490196 0.697098 0.208501 0.480835) (0.494118 0.703532 0.210638 0.479049) (0.498039 0.709962 0.212797 0.477201) (0.501961 0.716387 0.214982 0.475290) (0.505882 0.722805 0.217194 0.473316) (0.509804 0.729216 0.219437 0.471279) (0.513725 0.735616 0.221713 0.469180) (0.517647 0.742004 0.224025 0.467018) (0.521569 0.748378 0.226377 0.464794) (0.525490 0.754737 0.228772 0.462509) (0.529412 0.761077 0.231214 0.460162) (0.533333 0.767398 0.233705 0.457755) (0.537255 0.773695 0.236249 0.455289) (0.541176 0.779968 0.238851 0.452765) (0.545098 0.786212 0.241514 0.450184) (0.549020 0.792427 0.244242 0.447543) (0.552941 0.798608 0.247040 0.444848) (0.556863 0.804752 0.249911 0.442102) (0.560784 0.810855 0.252861 0.439305) (0.564706 0.816914 0.255895 0.436461) (0.568627 0.822926 0.259016 0.433573) (0.572549 0.828886 0.262229 0.430644) (0.576471 0.834791 0.265540 0.427671) (0.580392 0.840636 0.268953 0.424666) (0.584314 0.846416 0.272473 0.421631) (0.588235 0.852126 0.276106 0.418573) (0.592157 0.857763 0.279857 0.415496) (0.596078 0.863320 0.283729 0.412403) (0.600000 0.868793 0.287728 0.409303) (0.603922 0.874176 0.291859 0.406205) (0.607843 0.879464 0.296125 0.403118) (0.611765 0.884651 0.300530 0.400047) (0.615686 0.889731 0.305079 0.397002) (0.619608 0.894700 0.309773 0.393995) (0.623529 0.899552 0.314616 0.391037) (0.627451 0.904281 0.319610 0.388137) (0.631373 0.908884 0.324755 0.385308) (0.635294 0.913354 0.330052 0.382563) (0.639216 0.917689 0.335500 0.379915) (0.643137 0.921884 0.341098 0.377376) (0.647059 0.925937 0.346844 0.374959) (0.650980 0.929845 0.352734 0.372677) (0.654902 0.933606 0.358764 0.370541) (0.658824 0.937221 0.364929 0.368567) (0.662745 0.940687 0.371224 0.366762) (0.666667 0.944006 0.377643 0.365136) (0.670588 0.947180 0.384178 0.363701) (0.674510 0.950210 0.390820 0.362468) (0.678431 0.953099 0.397563 0.361438) (0.682353 0.955849 0.404400 0.360619) (0.686275 0.958464 0.411324 0.360014) (0.690196 0.960949 0.418323 0.359630) (0.694118 0.963310 0.425390 0.359469) (0.698039 0.965549 0.432519 0.359529) (0.701961 0.967671 0.439703 0.359810) (0.705882 0.969680 0.446936 0.360311) (0.709804 0.971582 0.454210 0.361030) (0.713725 0.973381 0.461520 0.361965) (0.717647 0.975082 0.468861 0.363111) (0.721569 0.976690 0.476226 0.364466) (0.725490 0.978210 0.483612 0.366025) (0.729412 0.979645 0.491014 0.367783) (0.733333 0.981000 0.498428 0.369734) (0.737255 0.982279 0.505851 0.371874) (0.741176 0.983485 0.513280 0.374198) (0.745098 0.984622 0.520713 0.376698) (0.749020 0.985693 0.528148 0.379371) (0.752941 0.986700 0.535582 0.382210) (0.756863 0.987646 0.543015 0.385210) (0.760784 0.988533 0.550446 0.388365) (0.764706 0.989363 0.557873 0.391671) (0.768627 0.990138 0.565296 0.395122) (0.772549 0.990871 0.572706 0.398714) (0.776471 0.991558 0.580107 0.402441) (0.780392 0.992196 0.587502 0.406299) (0.784314 0.992785 0.594891 0.410283) (0.788235 0.993326 0.602275 0.414390) (0.792157 0.993834 0.609644 0.418613) (0.796078 0.994309 0.616999 0.422950) (0.800000 0.994738 0.624350 0.427397) (0.803922 0.995122 0.631696 0.431951) (0.807843 0.995480 0.639027 0.436607) (0.811765 0.995810 0.646344 0.441361) (0.815686 0.996096 0.653659 0.446213) (0.819608 0.996341 0.660969 0.451160) (0.823529 0.996580 0.668256 0.456192) (0.827451 0.996775 0.675541 0.461314) (0.831373 0.996925 0.682828 0.466526) (0.835294 0.997077 0.690088 0.471811) (0.839216 0.997186 0.697349 0.477182) (0.843137 0.997254 0.704611 0.482635) (0.847059 0.997325 0.711848 0.488154) (0.850980 0.997351 0.719089 0.493755) (0.854902 0.997351 0.726324 0.499428) (0.858824 0.997341 0.733545 0.505167) (0.862745 0.997285 0.740772 0.510983) (0.866667 0.997228 0.747981 0.516859) (0.870588 0.997138 0.755190 0.522806) (0.874510 0.997019 0.762398 0.528821) (0.878431 0.996898 0.769591 0.534892) (0.882353 0.996727 0.776795 0.541039) (0.886275 0.996571 0.783977 0.547233) (0.890196 0.996369 0.791167 0.553499) (0.894118 0.996162 0.798348 0.559820) (0.898039 0.995932 0.805527 0.566202) (0.901961 0.995680 0.812706 0.572645) (0.905882 0.995424 0.819875 0.579140) (0.909804 0.995131 0.827052 0.585701) (0.913725 0.994851 0.834213 0.592307) (0.917647 0.994524 0.841387 0.598983) (0.921569 0.994222 0.848540 0.605696) (0.925490 0.993866 0.855711 0.612482) (0.929412 0.993545 0.862859 0.619299) (0.933333 0.993170 0.870024 0.626189) (0.937255 0.992831 0.877168 0.633109) (0.941176 0.992440 0.884330 0.640099) (0.945098 0.992089 0.891470 0.647116) (0.949020 0.991688 0.898627 0.654202) (0.952941 0.991332 0.905763 0.661309) (0.956863 0.990930 0.912915 0.668481) (0.960784 0.990570 0.920049 0.675675) (0.964706 0.990175 0.927196 0.682926) (0.968627 0.989815 0.934329 0.690198) (0.972549 0.989434 0.941470 0.697519) (0.976471 0.989077 0.948604 0.704863) (0.980392 0.988717 0.955742 0.712242) (0.984314 0.988367 0.962878 0.719649) (0.988235 0.988033 0.970012 0.727077) (0.992157 0.987691 0.977154 0.734536) (0.996078 0.987387 0.984288 0.742002) (1.000000 0.987053 0.991438 0.749504)) )(cxgetvar 'cmap-list)))
```