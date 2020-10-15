# Struktur preview & themes themplates
```
{% load static %}
{% load compress %}
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">   
	<title>Template Wedding | Homepage</title>
	<link rel="shortcut icon" href="{% static 'rsvp/wedding/emma_norman/images/ico.ico' %}">
	<!-- Customize css -->
	{% compress css %}
		{% include 'static/css.html' %}
		<link rel="stylesheet" type="text/css" href="{% static 'rsvp/wedding/emma_norman/style-wedding-4.css' %}">
	{% endcompress %}
	<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
</head>
<body>
	<!-- Content -->
	<div id="homepage"></div>

	<!-- Customize js -->
	<script>
		new WOW().init();
	</script>
	{% compress js %}
		{% include 'static/js.html' %}
		<script type="text/javascript" src="{% static 'rsvp/wedding/emma_norman/app.js' %}"></script>
	{% endcompress %}
	<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
	<script>
		AOS.init({
			duration: 1500,
		});
	</script>
</body>
</html>


    <!-- Customize css -->
    {% compress css %}
        <link rel="stylesheet" type="text/css" href="{% static 'css/animation.css' %}">
        <link rel="stylesheet" type="text/css" href="{% static 'css/default.css' %}">
        <link rel="stylesheet" href="{% static 'features/animatecss/animate.min.css' %}">
        <link rel="stylesheet" href="{% static 'node_modules/bootstrap/dist/css/bootstrap.min.css' %}">
        <link rel="stylesheet" href="{% static 'node_modules/font-awesome/css/font-awesome.min.css' %}">
        <link rel="stylesheet" href="{% static 'node_modules/owl.carousel/dist/assets/owl.carousel.min.css' %}">
        <link rel="stylesheet" href="{% static 'node_modules/owl.carousel/dist/assets/owl.theme.default.min.css' %}">
        <link rel="stylesheet" type="text/css" href="{% static 'rsvp/birthday/aaron/style-birthday-4.css' %}">
    {% endcompress %}


    	<link rel="stylesheet" type="text/css" href="https://dev.reservasidulu.com/static/css/animation.css">
        <link rel="stylesheet" type="text/css" href="https://dev.reservasidulu.com/static/css/default.css">
        <link rel="stylesheet" type="text/css" href="https://dev.reservasidulu.com/static/rsvp/birthday/aaron/style-birthday-4.css">
        <link rel="stylesheet" href="https://dev.reservasidulu.com/static/features/animatecss/animate.min.css">
        <link rel="stylesheet" href="https://dev.reservasidulu.com/static/node_modules/bootstrap/dist/css/bootstrap.min.css">
        <link rel="stylesheet" href="https://dev.reservasidulu.com/static/node_modules/font-awesome/css/font-awesome.min.css">
        <link rel="stylesheet" href="https://dev.reservasidulu.com/static/node_modules/owl.carousel/dist/assets/owl.carousel.min.css">
        <link rel="stylesheet" href="https://dev.reservasidulu.com/static/node_modules/owl.carousel/dist/assets/owl.theme.default.min.css">



        <link rel="stylesheet" href="/static/features/animatecss/animate.min.css">
        <link rel="stylesheet" href="/static/node_modules/bootstrap/dist/css/bootstrap.min.css">
        <link rel="stylesheet" href="/static/node_modules/font-awesome/css/font-awesome.min.css">
        <link rel="stylesheet" href="/static/node_modules/owl.carousel/dist/assets/owl.carousel.min.css">
        <link rel="stylesheet" href="/static/node_modules/owl.carousel/dist/assets/owl.theme.default.min.css">
        <link rel="stylesheet" type="text/css" href="/static/css/animation.css">
        <link rel="stylesheet" type="text/css" href="/static/css/default.css">
        <link rel="stylesheet" type="text/css" href="/static/rsvp/birthday/aaron/style-birthday-4.css">


```

# Templates Theme

## Templates Birthday
	- aaron
		<!-- Logo -->
		1. Logo 						= {{ x.img_logo.url }}
		<!-- Banner -->
		2. Banner Sub Title				= {{ x.banner_subtitle }}
		3. Banner Title 				= {{ x.banner_title }}
		4. Banner Background 			= {{ x.banner_bg.url }}
		5. Banner Background Mobile		= {{ x.banner_bg_mobile.url }}
		<!-- About -->
		6. About Name 					= {{ x.about_name }}
		7. About Age 					= {{ x.about_age }}
		8. About Image 1				= {{ x.about_image1.url }}
		9. About Image 2				= {{ x.about_image2.url }}
		10. About Image 3				= {{ x.about_image3.url }}
		11. About Image 4				= {{ x.about_image4.url }}
		12. About Image 5				= {{ x.about_image5.url }}
		13. About Image 6				= {{ x.about_image6.url }}
		14. About Image 7				= {{ x.about_image7.url }}
		15. About Image 8				= {{ x.about_image8.url }}
		16. About Image 9				= {{ x.about_image9.url }}
		17. About Image 10				= {{ x.about_image10.url }}
		<!-- Date and Place -->
		18. Date and Place Day			= {{ x.dap_day }}
		19. Date and Place Date			= {{ x.dap_date }}
		20. Date and Place Time			= {{ x.dap_time }}
		21. Date and Place Place		= {{ x.dap_place }}
		22. Date and Place Address		= {{ x.dap_address }}
		23. Date and Place Dresscode	= {{ x.dap_dress }}
		<!-- RSVP -->
		24. Invitation PDF				= {{ x.inv_pdf.url }}
	- anastasia
		<!-- Banner -->
		1. Banner Name					= {{ x.banner_name }}
		2. Banner Age 				 	= {{ x.banner_age }}
		3. Banner Brief 				= {{ x.banner_brief }}
		4. Banner Background 			= {{ x.banner_bg.url }}
		5. Banner Background Mobile		= {{ x.banner_bg_mobile.url }}
		<!-- Gallery -->
		6. Gallery Image 1				= {{ x.gallery_image1.url }}
		7. Gallery Image 2				= {{ x.gallery_image2.url }}
		8. Gallery Image 3				= {{ x.gallery_image3.url }}
		9. Gallery Image 4				= {{ x.gallery_image4.url }}
		10. Gallery Image 5				= {{ x.gallery_image5.url }}
		<!-- Date and Place -->
		11. Date and Place Date			= {{ x.dap_date }}
		12. Date and Place Day			= {{ x.dap_day }}
		13. Date and Place Time			= {{ x.dap_time }}
		14. Date and Place Place		= {{ x.dap_place }}
		15. Date and Place Address		= {{ x.dap_address }}
		16. Date and Place Dresscode	= {{ x.dap_dress }}
		<!-- RSVP -->
		17. Invitation PDF				= {{ x.inv_pdf.url }}
	- christine
		<!-- Banner -->
		1. Banner Sub Title				= {{ x.banner_subtitle }}
		2. Banner Title 				= {{ x.banner_title }}
		3. Banner Background 			= {{ x.banner_bg.url }}
		4. Banner Background Mobile		= {{ x.banner_bg_mobile.url }}
		<!-- About -->
		5. About Name 					= {{ x.about_name }}
		6. About Age 					= {{ x.about_age }}
		7. About Brief 					= {{ x.about_brief }}
		<!-- Brief -->
		8. Brief Image 1				= {{ x.brief_image1.url }}
		9. Brief Image 2				= {{ x.brief_image2.url }}
		10. Brief Image 3				= {{ x.brief_image3.url }}
		11. Brief Description 			= {{ x.brief_desc }}
		<!-- Date and Place -->
		12. Date and Place Day			= {{ x.dap_day }}
		13. Date and Place Date			= {{ x.dap_date }}
		14. Date and Place Time			= {{ x.dap_time }}
		15. Date and Place Place		= {{ x.dap_place }}
		16. Date and Place Address		= {{ x.dap_address }}
		17. Date and Place Dresscode	= {{ x.dap_dress }}
		<!-- RSVP -->
		18. Invitation PDF				= {{ x.inv_pdf.url }}
	- diana_ross
		<!-- Banner -->
		1. Banner Logo 					= {{ x.banner_logo.url }}
		2. Banner Logo Mobile			= {{ x.banner_logo_mobile.url }}
		<!-- About -->
		3. About Name 					= {{ x.about_name }}
		4. About Brief 					= {{ x.about_brief }}
		5. About Image	 				= {{ x.about_image.url }}
		<!-- Date and Place -->
		6. Date and Place Brief			= {{ x.dap_brief }}
		7. Date and Place Date			= {{ x.dap_date }}
		8. Date and Place Month			= {{ x.dap_month }}
		9. Date and Place Year			= {{ x.dap_year }}
		10. Date and Place Time			= {{ x.dap_time }}
		11. Date and Place Place		= {{ x.dap_place }}
		12. Date and Place Room			= {{ x.dap_room }}
		13. Date and Place Maps 		= {{ x.dap_maps }}
		14. Date and Place Image Place	= {{ x.dap_place_image.url }}
		15. Date and Place Description	= {{ x.dap_desc }}
		16. Date and Place Dresscode	= {{ x.dap_dress }}
		17. Date and Place Image Desc	= {{ x.dap_desc_image.url }}
		<!-- Gallery -->
		18. Gallery Image 1				= {{ x.gallery_image1.url }}
		19. Gallery Image 2				= {{ x.gallery_image2.url }}
		20. Gallery Image 3				= {{ x.gallery_image3.url }}
		21. Gallery Image 4				= {{ x.gallery_image4.url }}
		22. Gallery Image 5				= {{ x.gallery_image5.url }}
		23. Gallery Image 6				= {{ x.gallery_image6.url }}
		24. Gallery Image 7				= {{ x.gallery_image7.url }}
		25. Gallery Image 8				= {{ x.gallery_image8.url }}
		26. Gallery Image 9				= {{ x.gallery_image9.url }}
		<!-- RSVP -->
		27. Invitation PDF				= {{ x.inv_pdf.url }}

## Templates Event
	- 10year_reunion
		<!-- Banner -->
		1. Banner Image 				= {{ x.banner_image.url }}
		2. Banner Name					= {{ x.banner_name }}
		3. Banner Hastag 1				= {{ x.banner_hastag1 }}
		4. Banner Title 				= {{ x.banner_title }}
		5. Banner Year 					= {{ x.banner_year }}
		6. Banner Hastag 2 				= {{ x.banner_hastag2 }}
		<!-- Date -->
		7. Date Hastag					= {{ x.date_hastag }}
		8. Date Day						= {{ x.date_day }}
		9. Date Date					= {{ x.date_date }}
		10. Date Time					= {{ x.date_time }}
		<!-- Place -->
		11. Place Hastag				= {{ x.place_hastag }}
		12. Place At					= {{ x.place_at }}
		13. Place Address				= {{ x.place_address }}
		<!-- Rundown -->
		14. Rundown Time 1				= {{ x.rundown_time1 }}
		15. Rundown Event 1				= {{ x.rundown_event1 }}
		16. Rundown Time 2				= {{ x.rundown_time2 }}
		17. Rundown Event 2				= {{ x.rundown_event2 }}
		18. Rundown Time 3				= {{ x.rundown_time3 }}
		19. Rundown Event 3				= {{ x.rundown_event3 }}
		20. Rundown Time 4				= {{ x.rundown_time4 }}
		21. Rundown Event 4				= {{ x.rundown_event4 }}
		22. Rundown Time 5				= {{ x.rundown_time5 }}
		23. Rundown Event 5				= {{ x.rundown_event5 }}
		24. Rundown Time 6				= {{ x.rundown_time6 }}
		25. Rundown Event 6				= {{ x.rundown_event6 }}
		26. Rundown Time 7				= {{ x.rundown_time7 }}
		27. Rundown Event 7				= {{ x.rundown_event7 }}
		28. Rundown Time 8				= {{ x.rundown_time8 }}
		29. Rundown Event 8				= {{ x.rundown_event8 }}
		30. Rundown Time 9				= {{ x.rundown_time9 }}
		31. Rundown Event 9				= {{ x.rundown_event9 }}
		<!-- RSVP -->
		31. Invitation PDF				= {{ x.inv_pdf.url }}
	- 20year_reunion
		<!-- Logo -->
		1. Logo 						= {{ x.img_logo.url }}
		<!-- Banner -->
		2. Banner Background 1 			= {{ x.banner_bg1.url }}
		3. Banner Background Mobile	1	= {{ x.banner_bg_mobile1.url }}
		4. Banner Background 2 			= {{ x.banner_bg2.url }}
		5. Banner Background Mobile	2	= {{ x.banner_bg_mobile2.url }}
		<!-- About -->
		6. About Image 1				= {{ x.about_image1.url }}
		7. About Image 2				= {{ x.about_image2.url }}
		8. About Name 					= {{ x.about_name }}
		9. About Title 					= {{ x.about_title }}
		10. About Year 					= {{ x.about_year }}
		11. About Brief					= {{ x.about_brief }}
		<!-- Date and Place -->
		12. Date and Place Title		= {{ x.dap_title }}
		13. Date and Place Day			= {{ x.dap_day }}
		14. Date and Place Date			= {{ x.dap_date }}
		15. Date and Place Time			= {{ x.dap_time }}
		16. Date and Place Address		= {{ x.dap_address }}
		<!-- Gallery -->
		17. Gallery Image 1				= {{ x.gallery_image1.url }}
		18. Gallery Title 1				= {{ x.gallery_title1 }}
		19. Gallery Image 2				= {{ x.gallery_image2.url }}
		20. Gallery Title 2				= {{ x.gallery_title2 }}
		21. Gallery Title 3				= {{ x.gallery_title3 }}
		22. Gallery Image 3				= {{ x.gallery_image3.url }}
		23. Gallery Title 4				= {{ x.gallery_title4 }}
		24. Gallery Image 4				= {{ x.gallery_image14.url }}
		<!-- Rundown -->
		25. Rundown Time 1				= {{ x.rundown_time1 }}
		26. Rundown Event 1				= {{ x.rundown_event1 }}
		27. Rundown Time 2				= {{ x.rundown_time2 }}
		28. Rundown Event 2				= {{ x.rundown_event2 }}
		29. Rundown Time 3				= {{ x.rundown_time3 }}
		30. Rundown Event 3				= {{ x.rundown_event3 }}
		31. Rundown Time 4				= {{ x.rundown_time4 }}
		32. Rundown Event 4				= {{ x.rundown_event4 }}
		33. Rundown Time 5				= {{ x.rundown_time5 }}
		34. Rundown Event 5				= {{ x.rundown_event5 }}
		35. Rundown Time 6				= {{ x.rundown_time6 }}
		36. Rundown Event 6				= {{ x.rundown_event6 }}
		37. Rundown Time 7				= {{ x.rundown_time7 }}
		38. Rundown Event 7				= {{ x.rundown_event7 }}
		39. Rundown Time 8				= {{ x.rundown_time8 }}
		40. Rundown Event 8				= {{ x.rundown_event8 }}
		<!-- RSVP -->
		41. Invitation PDF				= {{ x.inv_pdf.url }}
	- brotherfield
		<!-- Logo -->
		1. Logo 						= {{ x.img_logo.url }}
		2. Instagram 					= {{ x.instagram }}
		3. Whatsapp 					= {{ x.wa }}
		<!-- Banner -->
		4. Banner Image 				= {{ x.banner_image.url }}
		5. Banner City 					= {{ x.banner_city }}
		<!-- About -->
		6. About Title 					= {{ x.about_title }}
		7. About Brief 					= {{ x.about_brief }}
		8. About Image 1				= {{ x.about_image1.url }}
		9. About Image 2				= {{ x.about_image2.url }}
		<!-- Venue -->
		10. Venue Date					= {{ x.venue_date }}
		11. Venue Maps 					= {{ x.venue_maps }}
		12. Venue Start					= {{ x.venue_start }}
		13. Venue End					= {{ x.venue_end }}
		14. Venue At						= {{ x.venue_at }}
		15. Venue Address				= {{ x.venue_address }}
		16. Venue Dresscode				= {{ x.venue_dress }}
		<!-- Menus -->
		17. Menus Image 1				= {{ x.menus_image1.url }}
		18. Menus Image 2				= {{ x.menus_image2.url }}
		19. Menus Image 3				= {{ x.menus_image3.url }}
		20. Menus Image 4				= {{ x.menus_image4.url }}
		21. Menus Food Content			= {{ x.menus_food_content }}
		22. Menus Drink Content			= {{ x.menus_drink_content }}
		<!-- Guest -->
		23. Guest Image 1				= {{ x.guest_image1.url }}
		24. Guest Name 1				= {{ x.guest_name1 }}
		25. Guest Image 2				= {{ x.guest_image2.url }}
		26. Guest Name 2				= {{ x.guest_name2 }}
		<!-- RSVP -->
		27. RSVP Image					= {{ x.rsvp_image.url }}
		28. Invitation PDF				= {{ x.inv_pdf.url }}
	- christmas_dinner
		<!-- Banner -->
		3. Banner Title 				= {{ x.banner_title }}
		<!-- About -->
		2. About Sub Title				= {{ x.about_subtitle }}
		3. About Title 					= {{ x.about_title }}
		4. About Background 			= {{ x.about_bg.url }}
		<!-- Date and Place -->
		18. Date and Place Day			= {{ x.dap_day }}
		19. Date and Place Date			= {{ x.dap_date }}
		20. Date and Place Time			= {{ x.dap_time }}
		21. Date and Place Place		= {{ x.dap_place }}
		22. Date and Place Address		= {{ x.dap_address }}
		22. Date and Place Contact		= {{ x.dap_contact }}
		23. Date and Place Dresscode	= {{ x.dap_dress }}
		22. Date and Place Things		= {{ x.dap_things }}
		11. Date and Place Maps 		= {{ x.dap_maps }}
		<!-- Rundown -->
		14. Rundown Time 1				= {{ x.rundown_time1 }}
		15. Rundown Event 1				= {{ x.rundown_event1 }}
		16. Rundown Time 2				= {{ x.rundown_time2 }}
		17. Rundown Event 2				= {{ x.rundown_event2 }}
		18. Rundown Time 3				= {{ x.rundown_time3 }}
		19. Rundown Event 3				= {{ x.rundown_event3 }}
		20. Rundown Time 4				= {{ x.rundown_time4 }}
		21. Rundown Event 4				= {{ x.rundown_event4 }}
		22. Rundown Time 5				= {{ x.rundown_time5 }}
		23. Rundown Event 5				= {{ x.rundown_event5 }}
		24. Rundown Time 6				= {{ x.rundown_time6 }}
		25. Rundown Event 6				= {{ x.rundown_event6 }}
		<!-- RSVP -->
		24. Invitation PDF				= {{ x.inv_pdf.url }}
	- lacasadepapel
		<!-- Banner -->
		1. Banner Background 			= {{ x.banner_bg.url }}
		2. Banner Background Mobile		= {{ x.banner_bg_mobile.url }}
		3. Banner Title 1				= {{ x.banner_title1 }}
		4. Banner Title 2				= {{ x.banner_title2 }}
		5. Banner Sub Title				= {{ x.banner_subtitle }}
		<!-- Brief -->
		6. Brief Title 					= {{ x.brief_title }}
		7. Brief Description			= {{ x.brief_desc }}
		8. Brief Date					= {{ x.brief_date }}
		9. Brief Time			 		= {{ x.brief_time }}
		10. Brief Dresscode				= {{ x.brief_dress }}
		<!-- Location -->
		11. Location At	 				= {{ x.loc_at }}
		12. Location Detail 			= {{ x.loc_detail }}
		13. Location Link	 			= {{ x.loc_link }}
		14. Location Maps 				= {{ x.loc_maps }}
		<!-- Rundown -->
		15. Rundown Background 			= {{ x.rundown_image.url }}
		16. Rundown Time 1				= {{ x.rundown_time1 }}
		17. Rundown Event 1				= {{ x.rundown_event1 }}
		18. Rundown Time 2				= {{ x.rundown_time2 }}
		19. Rundown Event 2				= {{ x.rundown_event2 }}
		20. Rundown Time 3				= {{ x.rundown_time3 }}
		21. Rundown Event 3				= {{ x.rundown_event3 }}
		22. Rundown Time 4				= {{ x.rundown_time4 }}
		23. Rundown Event 4				= {{ x.rundown_event4 }}
		24. Rundown Time 5				= {{ x.rundown_time5 }}
		25. Rundown Event 5				= {{ x.rundown_event5 }}
		26. Rundown Time 6				= {{ x.rundown_time6 }}
		27. Rundown Event 6				= {{ x.rundown_event6 }}
		28. Rundown Time 7				= {{ x.rundown_time7 }}
		29. Rundown Event 7				= {{ x.rundown_event7 }}
		<!-- Partners -->
		30. Partners Image 1			= {{ x.partners_image1.url }}
		31. Partners Image 2			= {{ x.partners_image2.url }}
		32. Partners Image 3			= {{ x.partners_image3.url }}
		33. Partners Image 4			= {{ x.partners_image4.url }}
		34. Partners Image 5			= {{ x.partners_image5.url }}
		35. Partners Image 6			= {{ x.partners_image6.url }}
		36. Partners Image 7			= {{ x.partners_image7.url }}
		37. Partners Image 8			= {{ x.partners_image8.url }}
		38. Partners Image 9			= {{ x.partners_image9.url }}
		39. Partners Image 10			= {{ x.partners_image10.url }}
		<!-- Footer -->
		40. Footer Phone				= {{ x.footer_phone }}
		41. Footer Email				= {{ x.footer_email }}
		42. Invitation PDF				= {{ x.inv_pdf.url }}
	- music
		<!-- Banner -->
		1. Banner Logo 1 				= {{ x.banner_logo1.url }}
		2. Banner Logo 2				= {{ x.banner_logo2.url }}
		3. Banner Event Name			= {{ x.banner_event_name }}
		4. Banner At					= {{ x.banner_at }}
		5. Banner Room					= {{ x.banner_room }}
		6. Banner Date					= {{ x.banner_date }}
		<!-- Brief -->
		7. Brief Title 					= {{ x.brief_title }}
		8. Brief Video					= {{ x.brief_video.url }}
		<!-- LineUp -->
		9. Lineup Name 1 				= {{ x.lineup_name1 }}
		10. Lineup Image 1				= {{ x.lineup_image1.url }}
		11. Lineup Name 2 				= {{ x.lineup_name2 }}
		12. Lineup Image 2				= {{ x.lineup_image2.url }}
		13. Lineup Name 3 				= {{ x.lineup_name3 }}
		14. Lineup Image 3				= {{ x.lineup_image3.url }}
		15. Lineup Name 4 				= {{ x.lineup_name4 }}
		16. Lineup Image 4				= {{ x.lineup_image4.url }}
		<!-- Ticket -->
		17. Ticket Title 1				= {{ x.ticket_title1 }}
		18. Ticket Brief 1				= {{ x.ticket_brief1 }}
		19. Ticket Price 1				= {{ x.ticket_price1 }}
		20. Ticket Link 1 				= {{ x.ticket_link1 }}
		21. Ticket Title 2				= {{ x.ticket_title2 }}
		22. Ticket Brief 2				= {{ x.ticket_brief2 }}
		23. Ticket Price 2				= {{ x.ticket_price2 }}
		24. Ticket Link 2 				= {{ x.ticket_link2 }}
		25. Ticket Title 3				= {{ x.ticket_title3 }}
		26. Ticket Brief 3				= {{ x.ticket_brief3 }}
		27. Ticket Price 3				= {{ x.ticket_price3 }}
		28. Ticket Link 3 				= {{ x.ticket_link3 }}
		29. Ticket Title 4				= {{ x.ticket_title4 }}
		30. Ticket Brief 4				= {{ x.ticket_brief4 }}
		31. Ticket Price 4				= {{ x.ticket_price4 }}
		32. Ticket Link 4 				= {{ x.ticket_link4 }}
		33. Ticket Title 5				= {{ x.ticket_title5 }}
		34. Ticket Brief 5				= {{ x.ticket_brief5 }}
		35. Ticket Price 5				= {{ x.ticket_price5 }}
		36. Ticket Link 5 				= {{ x.ticket_link5 }}
		37. Ticket Title 6				= {{ x.ticket_title6 }}
		38. Ticket Brief 6				= {{ x.ticket_brief6 }}
		39. Ticket Price 6				= {{ x.ticket_price6 }}
		40. Ticket Link 6 				= {{ x.ticket_link6 }}
		41. Ticket Title 7				= {{ x.ticket_title7 }}
		42. Ticket Brief 7				= {{ x.ticket_brief7 }}
		43. Ticket Price 7				= {{ x.ticket_price7 }}
		44. Ticket Link 7 				= {{ x.ticket_link7 }}
		45. Ticket Title 8				= {{ x.ticket_title8 }}
		46. Ticket Brief 8				= {{ x.ticket_brief8 }}
		47. Ticket Price 8				= {{ x.ticket_price8 }}
		48. Ticket Link 8 				= {{ x.ticket_link8 }}
		<!-- Update -->
		49. Update More Update Link		= {{ x.update_more_link }}
		50. Update Title Highlight		= {{ x.update_title_hl }}
		51. Update Brief Highlight		= {{ x.update_brief_hl }}
		52. Update Link Highlight		= {{ x.update_link_hl }}
		53. Update Title 1				= {{ x.update_title1 }}
		54. Update Brief 1				= {{ x.update_brief1 }}
		55. Update Link 1				= {{ x.update_link1 }}
		56. Update Title 2				= {{ x.update_title2 }}
		57. Update Brief 2				= {{ x.update_brief2 }}
		58. Update Link 2				= {{ x.update_link2 }}
		59. Update Title 3				= {{ x.update_title3 }}
		60. Update Brief 3				= {{ x.update_brief3 }}
		61. Update Link 3				= {{ x.update_link3 }}
		62. Update Title 4				= {{ x.update_title4 }}
		63. Update Brief 4				= {{ x.update_brief4 }}
		64. Update Link 4				= {{ x.update_link4 }}
		<!-- Venue -->
		65. Venue Address				= {{ x.venue_address }}
		66. Venue Maps 					= {{ x.venue_maps }}
		<!-- About -->
		67. About Title 				= {{ x.about_title }}
		68. About Description			= {{ x.about_brief }}
		69. About Image 				= {{ x.about_image.url }}
		<!-- Sponsors -->
		70. Sponsors Title 1			= {{ x.sponsors_title1 }}
		71. Sponsors Logo 1				= {{ x.sponsors_logo1.url }}
		72. Sponsors Title 2			= {{ x.sponsors_title2 }}
		73. Sponsors Logo 2				= {{ x.sponsors_logo2.url }}
		74. Sponsors Title 3			= {{ x.sponsors_title3 }}
		75. Sponsors Logo 3				= {{ x.sponsors_logo3.url }}
		76. Sponsors Title 4			= {{ x.sponsors_title4 }}
		77. Sponsors Logo 4				= {{ x.sponsors_logo4.url }}
		78. Sponsors Title 5			= {{ x.sponsors_title5 }}
		79. Sponsors Logo 5				= {{ x.sponsors_logo5.url }}
	- oceandor
		<!-- Logo -->
		1. Logo 						= {{ x.img_logo.url }}
		<!-- Banner -->
		2. Banner Title 				= {{ x.banner_title }}
		3. Banner Sub Title				= {{ x.banner_subtitle }}
		4. Banner Button Text 			= {{ x.banner_button_text }}
		5. Banner Button Link 			= {{ x.banner_button_link }}
		6. Banner Image 				= {{ x.banner_image.url }}
		<!-- About -->
		7. About Name 					= {{ x.about_name }}
		8. About Brief 					= {{ x.about_brief }}
		9. About Button Text 			= {{ x.about_button_text }}
		10. About Button Link 			= {{ x.about_button_link }}
		11. About Image Highlight		= {{ x.about_image_hl.url }}
		12. About Image 1				= {{ x.about_image1.url }}
		13. About Image 2				= {{ x.about_image2.url }}
		<!-- Date and Place -->
		14. Date and Place Date			= {{ x.dap_date }}
		15. Date and Place Time			= {{ x.dap_time }}
		16. Date and Place Place		= {{ x.dap_place }}
		17. Date and Place Address		= {{ x.dap_address }}
		18. Date and Place Maps Link	= {{ x.dap_maps }}
		19. Date and Place Background	= {{ x.dap_bg.url }}
		<!-- Guest -->
		20. Guest Name 1				= {{ x.guest_name1 }}
		21. Guest Image Left 1			= {{ x.guest_image_l1.url }}
		22. Guest Image Right 1			= {{ x.guest_image_r1.url }}
		23. Guest Description 1			= {{ x.guest_desc1 }}
		24. Guest Name 2				= {{ x.guest_name2 }}
		25. Guest Image Left 2			= {{ x.guest_image_l2.url }}
		26. Guest Image Right 2			= {{ x.guest_image_r2.url }}
		27. Guest Description 2			= {{ x.guest_desc2 }}
		<!-- RSVP -->
		28. RSVP Brief 					= {{ x.rsvp_brief }}
		29. Invitation PDF				= {{ x.inv_pdf.url }}
	- seminary
		<!-- Logo -->
		1. Logo 						= {{ x.img_logo.url }}
		<!-- Banner -->
		2. Banner Title 				= {{ x.banner_title }}
		3. Banner Date					= {{ x.banner_date }}
		4. Banner Time					= {{ x.banner_time }}
		5. Banner At					= {{ x.banner_at }}
		<!-- About -->
		6. About Title 					= {{ x.about_title }}
		7. About Point 1				= {{ x.about_point1 }}
		8. About Point 2				= {{ x.about_point2 }}
		9. About Point 3				= {{ x.about_point3 }}
		10. About Point 4				= {{ x.about_point4 }}
		11. About Point 5				= {{ x.about_point5 }}
		12. About Point 6				= {{ x.about_point6 }}
		13. About Attendees 			= {{ x.about_attendees }}
		14. About Classes 				= {{ x.about_classes }}
		15. About Speakers				= {{ x.about_speakers }}
		<!-- Gallery -->
		16. Gallery Image 1				= {{ x.gallery_image1.url }}
		17. Gallery Image Mobile 1 		= {{ x.gallery_image_mobile1.url }}
		18. Gallery Image 2				= {{ x.gallery_image2.url }}
		19. Gallery Image Mobile 2 		= {{ x.gallery_image_mobile2.url }}
		20. Gallery Image 3				= {{ x.gallery_image3.url }}
		21. Gallery Image Mobile 3 		= {{ x.gallery_image_mobile3.url }}
		<!-- Speakers -->
		22. Speakers Image 1			= {{ x.speakers_image1.url }}
		23. Speakers Name 1				= {{ x.speakers_name1 }}
		24. Speakers Title 1			= {{ x.speakers_title1 }}
		25. Speakers Position 1			= {{ x.speakers_position1 }}
		26. Speakers Company 1			= {{ x.speakers_company1 }}
		27. Speakers Date 1				= {{ x.speakers_date1 }}
		28. Speakers Brief 1			= {{ x.speakers_brief1 }}
		29. Speakers Facebook 1			= {{ x.speakers_fb1 }}
		30. Speakers Twitter 1			= {{ x.speakers_twitter1 }}
		31. Speakers Whatsapp 1			= {{ x.speakers_wa1 }}
		32. Speakers Instagram 1		= {{ x.speakers_ig1 }}
		33. Speakers Image 2			= {{ x.speakers_image2.url }}
		34. Speakers Name 2				= {{ x.speakers_name2 }}
		35. Speakers Title 2			= {{ x.speakers_title2 }}
		36. Speakers Position 2			= {{ x.speakers_position2 }}
		37. Speakers Company 2			= {{ x.speakers_company2 }}
		38. Speakers Date 2				= {{ x.speakers_date2 }}
		39. Speakers Brief 2			= {{ x.speakers_brief2 }}
		40. Speakers Facebook 2			= {{ x.speakers_fb2 }}
		41. Speakers Twitter 2			= {{ x.speakers_twitter2 }}
		42. Speakers Whatsapp 2			= {{ x.speakers_wa2 }}
		43. Speakers Instagram 2		= {{ x.speakers_ig2 }}
		<!-- Schedule -->
		44. Schedule Home Date 1		= {{ x.sc_hm_date1 }}
		45. Schedule Home Name 1		= {{ x.sc_hm_name1 }}
		46. Schedule Home Title 1		= {{ x.sc_hm_title1 }}
		47. Schedule Home Brief 1		= {{ x.sc_hm_brief1 }}
		48. Schedule Home Date 2		= {{ x.sc_hm_date2 }}
		49. Schedule Home Name 2		= {{ x.sc_hm_name2 }}
		50. Schedule Home Title 2		= {{ x.sc_hm_title2 }}
		51. Schedule Home Brief 2		= {{ x.sc_hm_brief2 }}		
		52. Schedule Home Date 3		= {{ x.sc_hm_date3 }}
		53. Schedule Home Name 3		= {{ x.sc_hm_name3 }}
		54. Schedule Home Title 3		= {{ x.sc_hm_title3 }}
		55. Schedule Home Brief 3		= {{ x.sc_hm_brief3 }}
		56. Schedule Home Date 4		= {{ x.sc_hm_date4 }}
		57. Schedule Home Name 4		= {{ x.sc_hm_name4 }}
		58. Schedule Home Title 4		= {{ x.sc_hm_title4 }}
		59. Schedule Home Brief 4		= {{ x.sc_hm_brief4 }}
		60. Schedule Home Date 5		= {{ x.sc_hm_date5 }}
		61. Schedule Home Name 5		= {{ x.sc_hm_name5 }}
		62. Schedule Home Title 5		= {{ x.sc_hm_title5 }}
		63. Schedule Home Brief 5		= {{ x.sc_hm_brief5 }}
		64. Schedule Home Date 6		= {{ x.sc_hm_date6 }}
		65. Schedule Home Name 6		= {{ x.sc_hm_name6 }}
		66. Schedule Home Title 6		= {{ x.sc_hm_title6 }}
		67. Schedule Home Brief 6		= {{ x.sc_hm_brief6 }}
		68. Schedule Profile Date 1		= {{ x.sc_pf_date1 }}
		69. Schedule Profile Name 1		= {{ x.sc_pf_name1 }}
		70. Schedule Profile Title 1	= {{ x.sc_pf_title1 }}
		71. Schedule Profile Brief 1	= {{ x.sc_pf_brief1 }}
		72. Schedule Profile Date 2		= {{ x.sc_pf_date2 }}
		73. Schedule Profile Name 2		= {{ x.sc_pf_name2 }}
		74. Schedule Profile Title 2	= {{ x.sc_pf_title2 }}
		75. Schedule Profile Brief 2	= {{ x.sc_pf_brief2 }}
		76. Schedule Profile Date 3		= {{ x.sc_pf_date3 }}
		77. Schedule Profile Name 3		= {{ x.sc_pf_name3 }}
		78. Schedule Profile Title 3	= {{ x.sc_pf_title3 }}
		79. Schedule Profile Brief 3	= {{ x.sc_pf_brief3 }}
		80. Schedule Profile Date 4		= {{ x.sc_pf_date4 }}
		81. Schedule Profile Name 4		= {{ x.sc_pf_name4 }}
		82. Schedule Profile Title 4	= {{ x.sc_pf_title4 }}
		83. Schedule Profile Brief 4	= {{ x.sc_pf_brief4 }}
		84. Schedule Profile Date 5		= {{ x.sc_pf_date5 }}
		85. Schedule Profile Name 5		= {{ x.sc_pf_name5 }}
		86. Schedule Profile Title 5	= {{ x.sc_pf_title5 }}
		87. Schedule Profile Brief 5	= {{ x.sc_pf_brief5 }}
		88. Schedule Profile Date 6		= {{ x.sc_pf_date6 }}
		89. Schedule Profile Name 6		= {{ x.sc_pf_name6 }}
		90. Schedule Profile Title 6	= {{ x.sc_pf_title6 }}
		91. Schedule Profile Brief 6	= {{ x.sc_pf_brief6 }}
		92. Schedule Contact Date 1		= {{ x.sc_ct_date1 }}
		93. Schedule Contact Name 1		= {{ x.sc_ct_name1 }}
		94. Schedule Contact Title 1	= {{ x.sc_ct_title1 }}
		95. Schedule Contact Brief 1	= {{ x.sc_ct_brief1 }}
		96. Schedule Contact Date 2		= {{ x.sc_ct_date2 }}
		97. Schedule Contact Name 2		= {{ x.sc_ct_name2 }}
		98. Schedule Contact Title 2	= {{ x.sc_ct_title2 }}
		99. Schedule Contact Brief 2	= {{ x.sc_ct_brief2 }}
		100. Schedule Contact Date 3	= {{ x.sc_ct_date3 }}
		101. Schedule Contact Name 3	= {{ x.sc_ct_name3 }}
		102. Schedule Contact Title 3	= {{ x.sc_ct_title3 }}
		103. Schedule Contact Brief 3	= {{ x.sc_ct_brief3 }}
		104. Schedule Contact Date 4	= {{ x.sc_ct_date4 }}
		105. Schedule Contact Name 4	= {{ x.sc_ct_name4 }}
		106. Schedule Contact Title 4	= {{ x.sc_ct_title4 }}
		107. Schedule Contact Brief 4	= {{ x.sc_ct_brief4 }}
		108. Schedule Contact Date 5	= {{ x.sc_ct_date5 }}
		109. Schedule Contact Name 5	= {{ x.sc_ct_name5 }}
		110. Schedule Contact Title 5	= {{ x.sc_ct_title5 }}
		111. Schedule Contact Brief 5	= {{ x.sc_ct_brief5 }}
		112. Schedule Contact Date 6	= {{ x.sc_ct_date6 }}
		113. Schedule Contact Name 6	= {{ x.sc_ct_name6 }}
		114. Schedule Contact Title 6	= {{ x.sc_ct_title6 }}
		115. Schedule Contact Brief 6	= {{ x.sc_ct_brief6 }}
		<!-- Location -->
		116. Location At	 			= {{ x.loc_at }}
		117. Location Detail 			= {{ x.loc_detail }}
		118. Location Image	 			= {{ x.loc_image.url }}
		119. Location Maps 				= {{ x.loc_maps }}
		<!-- Sponsors -->
		120. Sponsors Image 1			= {{ x.sponsor_image1.url }}
		121. Sponsors Image 2			= {{ x.sponsor_image2.url }}
		122. Sponsors Image 3			= {{ x.sponsor_image3.url }}
		123. Sponsors Image 4			= {{ x.sponsor_image4.url }}
		124. Sponsors Image 5			= {{ x.sponsor_image5.url }}
		<!-- RSVP -->
		125. Invitation PDF				= {{ x.inv_pdf.url }}

## Templates Wedding
	- dylan_rose
	- emma_norman
		<!-- Logo -->
		1. Logo 						= {{ x.img_logo.url }}
		<!-- Banner -->
		2. Banner 1 					= {{ x.img_background1.url }}
		3. Banner 2						= {{ x.img_background2.url }}
		4. Banner 3						= {{ x.img_background3.url }}
		<!-- Our Story -->
		5. Quote 						= {{ x.about_quote }}
		6. Quote By 					= {{ x.about_quote_by }}
		7. Our Story Image 1			= {{ x.about_img1.url }}
		8. Our Story Image 2			= {{ x.about_img2.url }}
		9. Our Story Title 				= {{ x.about_title }}
		10. Our Story Brief 			= {{ x.about }}
		<!-- Invitation -->
		11. Ceremony Background			= {{ x.ceremony_img.url }}
		12. Ceremony Time 				= {{ x.ceremony_time }}
		13. Ceremony Location			= {{ x.ceremony_location }}
		14. Reception Background		= {{ x.reception_img.url }}
		15. Reception Time	 			= {{ x.reception_time }}
		16. Reception Location			= {{ x.reception_location }}
		<!-- Gallery -->
		17. Gallery Title 				= {{ x.gallery_title }}
		18. Gallery Brief				= {{ x.gallery_text }}
		19. Gallery Image 1				= {{ x.gallery1.url }}
		20. Gallery Image 2				= {{ x.gallery2.url }}
		21. Gallery Image 3				= {{ x.gallery3.url }}
		22. Gallery Image 4				= {{ x.gallery4.url }}
		<!-- RSVP -->
		23. RSVP Background				= {{ x.rsvp_img.url }}
	- jack_jane
	- liam_felicia
	- lucas_eli
	- natasha_bruce
	- peter_mary
	- steve_sharon
	- vicky_wanda
	- victor_karla

## Free
	- anastasia
	- christine
	- diana_ross
	- dylan_rose
	- natasha_bruce
	- steve_sharon

## Template Name
	- Wedding
		1. dylan_rose		= wedding_8
		2. emma_norman		= wedding_4
		3. jack_jane		= wedding_5
		4. liam_felicia		= wedding_3
		5. lucas_eli		= wedding_10
		6. natasha_bruce	= wedding_1
		7. peter_mary		= wedding_2
		8. steve_sharon		= wedding_9
		9. vicky_wanda		= wedding_6
		10. victor_karla	= wedding_victor
	- Birthday
		1. aaron			= birthday_4 
		2. anastasia		= birthday_2 
		3. christine		= birthday_3 
		4. diana_ross		= birthday_1 
	- Event
		1. 10year_reunion	= event_5
		2. 20year_reunion	= event_6
		3. brotherfield		= grand_opening
		4. christmas_dinner	= event_7
		5. lacasadepapel	= gala_dinner
		6. music			= event_8
		7. oceandor			= event_3
		8. seminary			= event_4
	- Free
		1. anastasia		= birthday_2_free
		2. christine		= birthday_3_free
		3. diana_ross		= birthday_1_free
		4. dylan_rose		= wedding_8_free
		5. natasha_bruce	= wedding_1_free
		6. steve_sharon		= wedding_9_free


## Template bug
	- Wedding
		1. dylan_rose		= https://dev.reservasidulu.com/themes/preview/precious-memories/
		2. emma_norman		= DONE
		3. jack_jane		= DONE
		4. liam_felicia		= DONE
		5. lucas_eli		= DONE
		6. natasha_bruce	= https://dev.reservasidulu.com/themes/preview/bushes-and-leaves/
		7. peter_mary		= https://dev.reservasidulu.com/themes/preview/scrapbook/
		8. steve_sharon		= DONE
		9. vicky_wanda		= DONE
		10. victor_karla	= https://dev.reservasidulu.com/themes/preview/us-againts-the-world/
	- Birthday
		1. aaron			= DONE
		2. anastasia		= https://dev.reservasidulu.com/themes/preview/pastel-party/
		3. christine		= DONE
		4. diana_ross		= DONE
	- Event
		1. 10year_reunion	= DONE
		2. 20year_reunion	= https://dev.reservasidulu.com/themes/preview/friendship/
		3. brotherfield		= https://dev.reservasidulu.com/themes/preview/colors-delight/
		4. christmas_dinner	= DONE
		5. lacasadepapel	= https://dev.reservasidulu.com/themes/preview/royal-invitation/
		6. music			= DONE
		7. oceandor			= DONE
		8. seminary			= https://dev.reservasidulu.com/themes/preview/tech-and-type/
	- Free
		1. anastasia		= DONE
		2. christine		= DONE
		3. diana_ross		= DONE
		4. dylan_rose		= DONE
		5. natasha_bruce	= https://dev.reservasidulu.com/themes/preview/free-bushes-and-leaves/
		6. steve_sharon		= https://dev.reservasidulu.com/themes/preview/free-blooming-feelings/