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
		32. Invitation PDF				= {{ x.inv_pdf.url }}
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
		24. Gallery Image 4				= {{ x.gallery_image4.url }}
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
		14. Venue At					= {{ x.venue_at }}
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
		1. Banner Title 				= {{ x.banner_title }}
		<!-- About -->
		2. About Sub Title				= {{ x.about_subtitle }}
		3. About Title 					= {{ x.about_title }}
		4. About Background 			= {{ x.about_bg.url }}
		<!-- Date and Place -->
		5. Date and Place Day			= {{ x.dap_day }}
		6. Date and Place Date			= {{ x.dap_date }}
		7. Date and Place Time			= {{ x.dap_time }}
		8. Date and Place Place		= {{ x.dap_place }}
		9. Date and Place Address		= {{ x.dap_address }}
		10. Date and Place Contact		= {{ x.dap_contact }}
		11. Date and Place Dresscode	= {{ x.dap_dress }}
		12. Date and Place Things		= {{ x.dap_things }}
		13. Date and Place Maps 		= {{ x.dap_maps }}
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
		26. Invitation PDF				= {{ x.inv_pdf.url }}
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
		<!-- Logo -->
		1. Logo 						= {{ x.img_logo.url }}
		<!-- Banner -->
		2. Banner Background 			= {{ x.banner_bg.url }}
		3. Banner Background Mobile		= {{ x.banner_bg_mobile.url }}
		<!-- Story -->
		4. Story Image 					= {{ x.story_image.url }}
		5. Story Brief 					= {{ x.story_brief }}
		<!-- Venue -->
		6. Venue Ceremony Day			= {{ x.vc_day }}
		7. Venue Ceremony Date			= {{ x.vc_date }}
		8. Venue Ceremony Time			= {{ x.vc_time }}
		9. Venue Ceremony Address		= {{ x.vc_address }}
		10. Venue Ceremony Dresscode	= {{ x.vc_dress }}
		11. Venue Ceremony Image		= {{ x.vc_image.url }}
		12. Venue Reception Day			= {{ x.vr_day }}
		13. Venue Reception Date		= {{ x.vr_date }}
		14. Venue Reception Time		= {{ x.vr_time }}
		15. Venue Reception Address		= {{ x.vr_address }}
		16. Venue Reception Dresscode	= {{ x.vr_dress }}
		17. Venue Reception Image		= {{ x.vr_image.url }}
		<!-- Accommodation -->
		18. Accommodation Image			= {{ x.acm_image.url }}
		19. Accommodation Place			= {{ x.acm_place }}
		20. Accommodation Address		= {{ x.acm_address }}
		21. Accommodation Note			= {{ x.acm_note }}
		<!-- Memories -->
		22. Memories Brief				= {{ x.memories_brief }}
		23. Memories Image 1			= {{ x.memories_image1.url }}
		24. Memories Image 2			= {{ x.memories_image2.url }}
		25. Memories Image 3			= {{ x.memories_image3.url }}
		26. Memories Image 4			= {{ x.memories_image4.url }}
		<!-- RSVP -->
		27. Invitation PDF				= {{ x.inv_pdf.url }}
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
		24. Invitation PDF				= {{ x.inv_pdf.url }}
	- jack_jane
		<!-- Logo -->
		1. Logo 						= {{ x.img_logo.url }}
		<!-- Banner -->
		2. Banner Date 					= {{ x.banner_date }}
		3. Banner Background 1 			= {{ x.banner_bg1.url }}
		4. Banner Background 2			= {{ x.banner_bg2.url }}
		5. Banner Background 3			= {{ x.banner_bg3.url }}
		<!-- About -->
		6. About Image 1				= {{ x.about_image1.url }}
		7. About Place 					= {{ x.about_place }}
		8. About Address 				= {{ x.about_address }}
		9. About Day 	 				= {{ x.about_day }}
		10. About Date 	 				= {{ x.about_date }}
		11. About Time 	 				= {{ x.about_time }}
		12. About Name 1	 			= {{ x.about_name1 }}
		13. About Brief 1				= {{ x.about_brief1 }}
		14. About Name 2	 			= {{ x.about_name2 }}
		15. About Brief 2				= {{ x.about_brief2 }}
		16. About Image 2				= {{ x.about_image2.url }}
		<!-- Album -->
		17. Album Image 1 				= {{ x.album_image1.url }}
		18. Album Image 2				= {{ x.album_image2.url }}
		19. Album Image 3				= {{ x.album_image3.url }}
		20. Album Image 4				= {{ x.album_image4.url }}
		21. Album Image 5				= {{ x.album_image5.url }}
		<!-- RSVP -->
		22. RSVP Image 					= {{ x.rsvp_image.url }}
		23. Invitation PDF				= {{ x.inv_pdf.url }}
	- liam_felicia
		<!-- Logo -->
		1. Initial Logo					= {{ x.initial_logo }}
		<!-- Banner -->
		2. Banner Title 				= {{ x.banner_title }}
		3. Banner Background 			= {{ x.banner_bg.url }}
		<!-- About -->
		4. About Image					= {{ x.about_image.url }}
		5. About Title 					= {{ x.about_title }}
		6. About Brief 					= {{ x.about_brief }}
		<!-- Venue -->
		7. Venue Ceremony Image			= {{ x.vc_image.url }}
		8. Venue Ceremony Day			= {{ x.vc_day }}
		9. Venue Ceremony Date			= {{ x.vc_date }}
		10. Venue Ceremony Time			= {{ x.vc_time }}
		11. Venue Ceremony Place		= {{ x.vc_place }}
		12. Venue Ceremony Address		= {{ x.vc_address }}
		13. Venue Reception Image		= {{ x.vr_image.url }}
		14. Venue Reception Day			= {{ x.vr_day }}
		15. Venue Reception Date		= {{ x.vr_date }}
		16. Venue Reception Time		= {{ x.vr_time }}
		17. Venue Reception Place		= {{ x.vr_place }}
		18. Venue Reception Address		= {{ x.vr_address }}
		<!-- Accommodation -->
		19. Accommodation Image			= {{ x.acm_image.url }}
		20. Accommodation Place			= {{ x.acm_place }}
		21. Accommodation Address		= {{ x.acm_address }}
		22. Accommodation Note			= {{ x.acm_note }}
		<!-- Gallery -->
		23. Gallery Image 1				= {{ x.gallery_image1.url }}
		24. Gallery Image 2				= {{ x.gallery_image2.url }}
		25. Gallery Image 3				= {{ x.gallery_image3.url }}
		26. Gallery Image 4				= {{ x.gallery_image4.url }}
		27. Gallery Image 5				= {{ x.gallery_image5.url }}
		<!-- RSVP -->
		28. Invitation PDF				= {{ x.inv_pdf.url }}
	- lucas_eli
		<!-- Banner -->
		1. Banner Date	 				= {{ x.banner_date }}
		2. Banner Title 				= {{ x.banner_title }}
		3. Banner Background 			= {{ x.banner_bg.url }}
		4. Banner Background Mobile		= {{ x.banner_bg_mobile.url }}
		<!-- Story -->
		5. Story Brief 					= {{ x.story_brief }}
		6. Story First Time Meet		= {{ x.story_meet }}
		7. Story First Time Date At		= {{ x.story_date_at }}
		8. Story Have Know Each Other	= {{ x.story_know_each_other }}
		9. Story Pet Name				= {{ x.story_pet }}
		10. Story Common Hobby			= {{ x.story_hobby }}
		11. Story Engaged At			= {{ x.story_engaged }}
		<!-- Gallery -->
		12. Gallery Image 1				= {{ x.gallery_image1.url }}
		13. Gallery Image 2				= {{ x.gallery_image2.url }}
		14. Gallery Image 3				= {{ x.gallery_image3.url }}
		15. Gallery Image 4				= {{ x.gallery_image4.url }}
		16. Gallery Image 5				= {{ x.gallery_image5.url }}
		17. Gallery Image 6				= {{ x.gallery_image6.url }}
		18. Gallery Image 7				= {{ x.gallery_image7.url }}
		19. Gallery Image 8				= {{ x.gallery_image8.url }}
		20. Gallery Image 9				= {{ x.gallery_image9.url }}
		<!-- Venue -->
		21. Venue Maps Image			= {{ x.vmaps_image.url }}
		22. Venue Ceremony Image		= {{ x.vc_image.url }}
		23. Venue Ceremony Date			= {{ x.vc_date }}
		24. Venue Ceremony Day			= {{ x.vc_day }}
		25. Venue Ceremony Time			= {{ x.vc_time }}
		26. Venue Ceremony Location		= {{ x.vc_loc }}
		27. Venue Ceremony Dresscode	= {{ x.vc_dress }}
		28. Venue Ceremony Parking	 	= {{ x.vc_parking }}
		29. Venue Reception Image		= {{ x.vr_image.url }}
		30. Venue Reception Date		= {{ x.vr_date }}
		31. Venue Reception Day			= {{ x.vr_day }}
		32. Venue Reception Time		= {{ x.vr_time }}
		33. Venue Reception Location	= {{ x.vr_loc }}
		34. Venue Reception Dresscode	= {{ x.vr_dress }}
		35. Venue Reception Parking	 	= {{ x.vr_parking }}
		<!-- Accommodation -->
		36. Accommodation Image			= {{ x.acm_image.url }}
		37. Accommodation Place			= {{ x.acm_place }}
		38. Accommodation Address		= {{ x.acm_address }}
		39. Accommodation Note			= {{ x.acm_note }}
		<!-- RSVP -->
		40. RSVP Popup Image			= {{ x.rsvp_popup_img.url }}
		41. RSVP Popup PIC Name			= {{ x.rsvp_popup_name }}
		42. RSVP Popup PIC Phone		= {{ x.rsvp_popup_phone }}
		43. Invitation PDF				= {{ x.inv_pdf.url }}
	- natasha_bruce
		<!-- Logo -->
		1. Logo 						= {{ x.img_logo.url }}
		<!-- Banner -->
		2. Banner Background 			= {{ x.banner_bg.url }}
		3. Banner Background Mobile		= {{ x.banner_bg_mobile.url }}
		<!-- Story -->
		4. Story Image 1				= {{ x.story_image1.url }}
		5. Story Image 2				= {{ x.story_image2.url }}
		6. Story Description			= {{ x.story_desc }}
		<!-- About -->
		7. About Groom Name				= {{ x.about_gr_name }}
		8. About Groom Brief			= {{ x.about_gr_brief }}
		9. About Groom Image			= {{ x.about_gr_image.url }}
		10. About Groom Image Mobile	= {{ x.about_gr_image_mobile.url }}
		11. About Bride Name			= {{ x.about_br_name }}
		12. About Bride Brief			= {{ x.about_br_brief }}
		13. About Bride Image			= {{ x.about_br_image.url }}
		14. About Bride Image Mobile	= {{ x.about_br_image_mobile.url }}
		<!-- Venue -->
		15. Venue Ceremony Image		= {{ x.vc_image.url }}
		16. Venue Ceremony Place		= {{ x.vc_place }}
		17. Venue Ceremony Day			= {{ x.vc_day }}
		18. Venue Ceremony Date			= {{ x.vc_date }}
		19. Venue Ceremony Time			= {{ x.vc_time }}
		20. Venue Ceremony Address		= {{ x.vc_address }}
		21. Venue Ceremony Dresscode	= {{ x.vc_dress }}
		22. Venue Ceremony Maps Link	= {{ x.vc_maps_link }}
		23. Venue Reception Image		= {{ x.vr_image.url }}
		24. Venue Reception Place		= {{ x.vr_place }}
		25. Venue Reception Day			= {{ x.vr_day }}
		26. Venue Reception Date		= {{ x.vr_date }}
		27. Venue Reception Time		= {{ x.vr_time }}
		28. Venue Reception Address		= {{ x.vr_address }}
		29. Venue Reception Dresscode	= {{ x.vr_dress }}
		30. Venue Reception Maps Link	= {{ x.vr_maps_link }}
		<!-- Accommodation -->
		31. Accommodation Image			= {{ x.acm_image.url }}
		32. Accommodation Place			= {{ x.acm_place }}
		33. Accommodation Sub Title		= {{ x.acm_subtitle }}
		34. Accommodation Brief			= {{ x.acm_brief }}
		35. Accommodation Maps Link		= {{ x.acm_maps_link }}
		<!-- Gallery -->
		36. Gallery Image 1				= {{ x.gallery_image1.url }}
		37. Gallery Image 2				= {{ x.gallery_image2.url }}
		38. Gallery Image 3				= {{ x.gallery_image3.url }}
		39. Gallery Image 4				= {{ x.gallery_image4.url }}
		<!-- RSVP -->
		40. Invitation PDF				= {{ x.inv_pdf.url }}
	- peter_mary
		<!-- Logo -->
		1. Logo 						= {{ x.img_logo.url }}
		2. Groom Name 					= {{ x.groom_name }}
		3. Bride Name 					= {{ x.bride_name }}
		<!-- Banner -->
		4. Banner Background 			= {{ x.banner_bg.url }}
		5. Banner Background Mobile		= {{ x.banner_bg_mobile.url }}
		<!-- About -->
		6. About Title 1				= {{ x.about_title1 }}
		7. About Brief 1				= {{ x.about_brief1 }}
		8. About Image Text	1 			= {{ x.about_image_text1 }}
		9. About Image 1				= {{ x.about_image1.url }}
		10. About Image Mobile 1		= {{ x.about_image1_mobile.url }}
		11. About Image 2				= {{ x.about_image2.url }}
		12. About Title 2				= {{ x.about_title2 }}
		13. About Brief 2				= {{ x.about_brief2 }}
		14. About Image 3				= {{ x.about_image3.url }}
		15. About Image Mobile 3		= {{ x.about_image3_mobile.url }}
		16. About Title 3				= {{ x.about_title3 }}
		17. About Brief 3				= {{ x.about_brief3 }}
		<!-- Venue -->
		18. Venue Image 				= {{ x.venue_image.url }}
		19. Venue Ceremony Date			= {{ x.vc_date }}
		20. Venue Ceremony Place		= {{ x.vc_place }}
		21. Venue Ceremony Address		= {{ x.vc_address }}
		22. Venue Ceremony Time			= {{ x.vc_time }}
		23. Venue Reception Date		= {{ x.vr_date }}
		24. Venue Reception Place		= {{ x.vr_place }}
		25. Venue Reception Address		= {{ x.vr_address }}
		26. Venue Reception Time		= {{ x.vr_time }}
		27. Venue Reception Dresscode	= {{ x.vr_dress }}
		<!-- Gallery -->
		28. Gallery Brief				= {{ x.gallery_brief }}
		29. Gallery Image 1				= {{ x.gallery_image1.url }}
		30. Gallery Image 2				= {{ x.gallery_image2.url }}
		31. Gallery Image 3				= {{ x.gallery_image3.url }}
		32. Gallery Image 4				= {{ x.gallery_image4.url }}
		33. Gallery Image 5				= {{ x.gallery_image5.url }}
		34. Gallery Image 6				= {{ x.gallery_image6.url }}
		35. Gallery Image 7				= {{ x.gallery_image7.url }}
		36. Gallery Image 8				= {{ x.gallery_image8.url }}
		<!-- Accommodation -->
		37. Accommodation Image			= {{ x.acm_image.url }}
		38. Accommodation Place			= {{ x.acm_place }}
		39. Accommodation Brief			= {{ x.acm_brief }}
		40. Accommodation Maps Link		= {{ x.acm_maps_link }}
		<!-- RSVP -->
		41. Invitation PDF				= {{ x.inv_pdf.url }}
	- steve_sharon
		<!-- Logo -->
		1. Logo 						= {{ x.img_logo.url }}
		<!-- Banner -->
		2. Banner Title 				= {{ x.banner_title }}
		3. Banner Background 			= {{ x.banner_bg.url }}
		<!-- Story -->
		4. Story Image 					= {{ x.story_image.url }}
		5. Story Brief 					= {{ x.story_brief }}
		6. Story Groom Name 			= {{ x.story_gr_name }}
		7. Story Groom Brief			= {{ x.story_gr_brief }}
		8. Story Bride Name 			= {{ x.story_br_name }}
		9. Story Bride Brief			= {{ x.story_br_brief }}
		<!-- Venue -->
		10. Venue Ceremony Title		= {{ x.vc_title }}
		11. Venue Ceremony Maps Link	= {{ x.vc_maps_link }}
		12. Venue Ceremony Date			= {{ x.vc_date }}
		13. Venue Ceremony Month Year	= {{ x.vc_my }}
		14. Venue Ceremony Time			= {{ x.vc_time }}
		15. Venue Ceremony Place		= {{ x.vc_place }}
		16. Venue Ceremony Address		= {{ x.vc_address }}
		17. Venue Ceremony Image		= {{ x.vc_image.url }}
		18. Venue Reception Title		= {{ x.vr_title }}
		19. Venue Reception Maps Link	= {{ x.vr_maps_link }}
		20. Venue Reception Date		= {{ x.vr_date }}
		21. Venue Reception Month Year	= {{ x.vr_my }}
		22. Venue Reception Time		= {{ x.vr_time }}
		23. Venue Reception Place		= {{ x.vr_place }}
		24. Venue Reception Address		= {{ x.vr_address }}
		25. Venue Reception Dresscode	= {{ x.vr_dress }}
		26. Venue Reception Image		= {{ x.vr_image.url }}
		<!-- Accommodation -->
		27. Accommodation Image			= {{ x.acm_image.url }}
		28. Accommodation Place			= {{ x.acm_place }}
		29. Accommodation Sub Title		= {{ x.acm_subtitle }}
		30. Accommodation Brief			= {{ x.acm_brief }}
		31. Accommodation Maps Link		= {{ x.acm_maps_link }}
		<!-- Gallery -->
		32. Gallery Brief				= {{ x.gallery_brief }}
		33. Gallery Image 1				= {{ x.gallery_image1.url }}
		34. Gallery Image 2				= {{ x.gallery_image2.url }}
		35. Gallery Image 3				= {{ x.gallery_image3.url }}
		36. Gallery Image 4				= {{ x.gallery_image4.url }}
		37. Gallery Image 5				= {{ x.gallery_image5.url }}
		38. Gallery Image 6				= {{ x.gallery_image6.url }}
		<!-- RSVP -->
		39. Invitation PDF				= {{ x.inv_pdf.url }}
	- vicky_wanda
		<!-- Logo -->
		1. Logogram						= {{ x.img_logogram.url }}
		2. Logotype						= {{ x.img_logotype.url }}
		3. Logotype Mobile	 			= {{ x.img_logotype_mobile.url }}
		<!-- Banner -->
		4. Banner Title 				= {{ x.banner_title }}
		5. Banner Background 			= {{ x.banner_bg.url }}
		<!-- About -->
		6. About Groom Image			= {{ x.about_gr_image.url }}
		7. About Groom Brief			= {{ x.about_gr_brief }}
		8. About Our Story Image		= {{ x.about_os_image.url }}
		9. About Our Story Brief 		= {{ x.about_os_brief }}
		10. About Bride Image			= {{ x.about_br_image.url }}
		11. About Bride Brief			= {{ x.about_br_brief }}
		<!-- Venue -->
		12. Venue Ceremony Month 		= {{ x.vc_month }}
		13. Venue Ceremony Date			= {{ x.vc_date }}
		14. Venue Ceremony Year	 		= {{ x.vc_year }}
		15. Venue Ceremony Place		= {{ x.vc_place }}
		16. Venue Ceremony Address		= {{ x.vc_address }}
		17. Venue Ceremony Image		= {{ x.vc_image.url }}
		18. Venue Ceremony Maps Link	= {{ x.vc_maps_link }}
		19. Venue Reception Month 		= {{ x.vr_month }}
		20. Venue Reception Date		= {{ x.vr_date }}
		21. Venue Reception Year	 	= {{ x.vr_year }}
		22. Venue Reception Place		= {{ x.vr_place }}
		23. Venue Reception Address		= {{ x.vr_address }}
		24. Venue Reception Dresscode	= {{ x.vr_dress }}
		25. Venue Reception Image		= {{ x.vr_image.url }}
		26. Venue Reception Maps Link	= {{ x.vr_maps_link }}
		<!-- Accommodation -->
		27. Accommodation Image			= {{ x.acm_image.url }}
		28. Accommodation Image Mobile	= {{ x.acm_image_mobile.url }}
		29. Accommodation Place			= {{ x.acm_place }}
		30. Accommodation Sub Title		= {{ x.acm_subtitle }}
		31. Accommodation Brief			= {{ x.acm_brief }}
		32. Accommodation Note			= {{ x.acm_note }}
		33. Accommodation Maps Link		= {{ x.acm_maps_link }}
		<!-- Gallery -->
		34. Gallery Image 1				= {{ x.gallery_image1.url }}
		35. Gallery Image 2				= {{ x.gallery_image2.url }}
		36. Gallery Image 3				= {{ x.gallery_image3.url }}
		37. Gallery Image 4				= {{ x.gallery_image4.url }}
		38. Gallery Image 5				= {{ x.gallery_image5.url }}
		39. Gallery Image 6				= {{ x.gallery_image6.url }}
		<!-- RSVP -->
		40. RSVP Image 					= {{ x.rsvp_image.url }}
		41. Invitation PDF				= {{ x.inv_pdf.url }}
	- victor_karla
		<!-- Logo -->
		1. Logo 						= {{ x.img_logo.url }}
		<!-- Invite -->
		2. Invite Brief 				= {{ x.invite_brief }}
		<!-- Story -->
		3. Story Background				= {{ x.story_bg.url }}
		4. Story Brief Mobile			= {{ x.story_brief_mobile }}
		<!-- Gallery -->
		5. Gallery Image Thumbnail		= {{ x.gallery_image_thumbnail.url }}
		6. Gallery Image Thumbnail Mobile = {{ x.gallery_image_thumbnail_mobile.url }}
		7. Gallery Image 1				= {{ x.gallery_image1.url }}
		8. Gallery Image 2				= {{ x.gallery_image2.url }}
		9. Gallery Image 3				= {{ x.gallery_image3.url }}
		10. Gallery Image 4				= {{ x.gallery_image4.url }}
		11. Gallery Image 5				= {{ x.gallery_image5.url }}
		12. Gallery Image 6				= {{ x.gallery_image6.url }}
		13. Gallery Image 7				= {{ x.gallery_image7.url }}
		14. Gallery Image 8				= {{ x.gallery_image8.url }}
		15. Gallery Image 9				= {{ x.gallery_image9.url }}
		<!-- Venue -->
		16. Venue Accommodation Place	= {{ x.va_place }}
		17. Venue Accommodation Brief	= {{ x.va_brief }}
		18. Venue Accommodation Address	= {{ x.va_address }}
		19. Venue Accommodation Note	= {{ x.va_note }}
		20. Venue Reception Place		= {{ x.vr_place }}
		21. Venue Reception Address		= {{ x.vr_address }}
		22. Venue Reception Date		= {{ x.vr_date }}
		23. Venue Reception Time 		= {{ x.vr_time }}
		24. Venue Reception Dresscode	= {{ x.vr_dress }}
		25. Venue Reception Note		= {{ x.vr_note }}
		26. Venue Ceremony Place		= {{ x.vc_place }}
		27. Venue Ceremony Address		= {{ x.vc_address }}
		28. Venue Ceremony Date			= {{ x.vc_date }}
		29. Venue Ceremony Time 		= {{ x.vc_time }}
		30. Venue Ceremony Dresscode	= {{ x.vc_dress }}
		31. Venue Ceremony Note			= {{ x.vc_note }}
		<!-- RSVP -->
		32. Invitation PDF				= {{ x.inv_pdf.url }}

## Free
	- anastasia
		1. Name							= {{ x.name }}
		2. Age 				 			= {{ x.age }}
		3. Image 						= {{ x.image.url }}
		4. Date 						= {{ x.date }}
		5. Day 							= {{ x.day }}
		6. Time 						= {{ x.time }}
		7. Place 						= {{ x.place }}
		8. Address 						= {{ x.address }}
		9. Dresscode 					= {{ x.dress }}
	- christine
		1. Name							= {{ x.name }}
		2. Age 				 			= {{ x.age }}
		3. Image 						= {{ x.image.url }}
		4. Day 							= {{ x.day }}
		5. Date 						= {{ x.date }}
		6. Time 						= {{ x.time }}
		7. Place 						= {{ x.place }}
		8. Address 						= {{ x.address }}
		9. Dresscode 					= {{ x.dress }}
	- diana_ross
		1. Name							= {{ x.name }}
		2. Image 						= {{ x.image.url }}
		3. Image Mobile					= {{ x.image_mobile.url }}
		4. Date 						= {{ x.date }}
		5. Month						= {{ x.month }}
		6. Year							= {{ x.year }}
		7. Time 						= {{ x.time }}
		8. Place 						= {{ x.place }}
		9. Place Image					= {{ x.place_image.url }}
		10. Address 					= {{ x.address }}
		11. Note 						= {{ x.note }}
		12. Note Image					= {{ x.note_image.url }}
		13. Dresscode 					= {{ x.dress }}
		14. Content Date 				= {{ x.ct_date }}
		15. Content Place				= {{ x.ct_place }}
		16. Content Note				= {{ x.ct_note }}
	- dylan_rose
		1. Name	Groom					= {{ x.name_groom }}
		2. Name	Bride					= {{ x.name_bride }}
		3. Logo 						= {{ x.logo.url }}
		4. Image 						= {{ x.image.url }}
		5. Image Mobile					= {{ x.image_mobile.url }}
		6. Venue Ceremony Day			= {{ x.vc_day }}
		7. Venue Ceremony Date			= {{ x.vc_date }}
		8. Venue Ceremony Time			= {{ x.vc_time }}
		9. Venue Ceremony Address		= {{ x.vc_address }}
		10. Venue Ceremony Dresscode	= {{ x.vc_dress }}
		11. Venue Reception Day			= {{ x.vr_day }}
		12. Venue Reception Date		= {{ x.vr_date }}
		13. Venue Reception Time		= {{ x.vr_time }}
		14. Venue Reception Address		= {{ x.vr_address }}
		15. Venue Reception Dresscode	= {{ x.vr_dress }}
	- natasha_bruce
		1. Name	Groom					= {{ x.name_groom }}
		2. Name	Bride					= {{ x.name_bride }}
		3. Image 						= {{ x.image.url }}
		4. Image Mobile					= {{ x.image_mobile.url }}
		5. Venue Ceremony Place			= {{ x.vc_place }}
		6. Venue Ceremony Date			= {{ x.vc_date }}
		7. Venue Ceremony Time			= {{ x.vc_time }}
		8. Venue Ceremony Brief			= {{ x.vc_brief }}
		9. Venue Reception Place		= {{ x.vr_place }}
		10. Venue Reception Date		= {{ x.vr_date }}
		11. Venue Reception Time		= {{ x.vr_time }}
		12. Venue Reception Brief		= {{ x.vr_brief }}
	- steve_sharon
		1. Name	Groom					= {{ x.name_groom }}
		2. Name	Bride					= {{ x.name_bride }}
		3. Image 						= {{ x.image.url }}
		4. Venue Ceremony Place 		= {{ x.vc_place }}
		5. Venue Ceremony Address		= {{ x.vc_address }}
		6. Venue Ceremony Date			= {{ x.vc_date }}
		7. Venue Ceremony Month			= {{ x.vc_month }}
		8. Venue Ceremony Year			= {{ x.vc_year }}
		9. Venue Ceremony Time			= {{ x.vc_time }}
		10. Venue Party Place 			= {{ x.vp_place }}
		11. Venue Party Address			= {{ x.vp_address }}
		12. Venue Party Date			= {{ x.vp_date }}
		13. Venue Party Month			= {{ x.vp_month }}
		14. Venue Party Year			= {{ x.vp_year }}
		15. Venue Party Time			= {{ x.vp_time }}

## Template Name
	- Birthday
		1. aaron			= birthday_4 		= Happy Dinosaur
		2. anastasia		= birthday_2 		= Pastel Party
		3. christine		= birthday_3 		= Fun Times
		4. diana_ross		= birthday_1 		= Polka Galore
	- Event
		1. 10year_reunion	= event_5			= Classroom
		2. 20year_reunion	= event_6			= Friendship
		3. brotherfield		= grand_opening 	= Colors Delight
		4. christmas_dinner	= event_7			= Christmas Jolly
		5. lacasadepapel	= gala_dinner		= Royal Invitation
		6. music			= event_8			= Soundtopia
		7. oceandor			= event_3			= Statement
		8. seminary			= event_4			= Tech and Type
	- Wedding
		1. dylan_rose		= wedding_8 		= Precious Memories
		2. emma_norman		= wedding_4 		= Sheer Blush
		3. jack_jane		= wedding_5 		= Soft Jade
		4. liam_felicia		= wedding_3 		= Passionate Bond
		5. lucas_eli		= wedding_10 		= Polaroid Love
		6. natasha_bruce	= wedding_1 		= Bushes and Leaves
		7. peter_mary		= wedding_2 		= Scrapbook
		8. steve_sharon		= wedding_9 		= Blooming Feelings
		9. vicky_wanda		= wedding_6 		= Terracotta
		10. victor_karla	= wedding_victor 	= Us Againts The World
	- Free
		1. anastasia		= birthday_2_free 	= Pastel Party
		2. christine		= birthday_3_free 	= Fun Times
		3. diana_ross		= birthday_1_free 	= Polka Galore
		4. dylan_rose		= wedding_8_free 	= Precious Memories
		5. natasha_bruce	= wedding_1_free 	= Bushes and Leaves
		6. steve_sharon		= wedding_9_free 	= Blooming Feelings

## Attendance
	- Birthday
		1. aaron			= Sudah dibuat, belum dicek tampilannya
		2. anastasia		= Sudah dibuat, belum dicek tampilannya
		3. christine		= Sudah dibuat, belum dicek tampilannya
		4. diana_ross		= Sudah dibuat, belum dicek tampilannya
	- Event
		1. 10year_reunion	= Sudah dibuat, belum dicek tampilannya
		2. 20year_reunion	= Sudah dibuat, belum dicek tampilannya
		3. brotherfield		= Sudah dibuat, belum dicek tampilannya
		4. christmas_dinner	= Sudah dibuat, belum dicek tampilannya
		5. lacasadepapel	= Sudah dibuat, belum dicek tampilannya
		6. music			= Tidak ada RSVP
		7. oceandor			= Sudah dibuat, belum dicek tampilannya
		8. seminary			= Sudah dibuat, belum dicek tampilannya
	- Wedding
		1. dylan_rose		= Sudah dibuat, belum dicek tampilannya
		2. emma_norman		= Sudah dibuat, belum dicek tampilannya
		3. jack_jane		= Sudah dibuat, belum dicek tampilannya
		4. liam_felicia		= Sudah dibuat, belum dicek tampilannya
		5. lucas_eli		= Sudah dibuat, belum dicek tampilannya
		6. natasha_bruce	= Sudah dibuat, belum dicek tampilannya
		7. peter_mary		= Sudah dibuat, belum dicek tampilannya
		8. steve_sharon		= Sudah dibuat, belum dicek tampilannya
		9. vicky_wanda		= Sudah dibuat, belum dicek tampilannya
		10. victor_karla	= Sudah dibuat, belum dicek tampilannya
	- Free
		1. anastasia		= 
		2. christine		= 
		3. diana_ross		= 
		4. dylan_rose		= 
		5. natasha_bruce	= 
		6. steve_sharon		= 

## Download Invitation
	- Birthday
		1. aaron			= DONE
		2. anastasia		= Belum ada design nya
		3. christine		= Belum ada design nya
		4. diana_ross		= DONE
	- Event
		1. 10year_reunion	= DONE
		2. 20year_reunion	= DONE
		3. brotherfield		= DONE
		4. christmas_dinner	= DONE
		5. lacasadepapel	= Fitur tidak ada
		6. music			= Fitur tidak ada
		7. oceandor			= DONE
		8. seminary			= DONE
	- Wedding
		1. dylan_rose		= DONE
		2. emma_norman		= DONE
		3. jack_jane		= DONE
		4. liam_felicia		= DONE
		5. lucas_eli		= DONE
		6. natasha_bruce	= DONE
		7. peter_mary		= DONE
		8. steve_sharon		= DONE
		9. vicky_wanda		= DONE
		10. victor_karla	= DONE
	- Free
		1. anastasia		= Fitur tidak ada
		2. christine		= Fitur tidak ada
		3. diana_ross		= Fitur tidak ada
		4. dylan_rose		= Fitur tidak ada
		5. natasha_bruce	= Fitur tidak ada
		6. steve_sharon		= Fitur tidak ada
## Popup RSVP
	- Birthday
		1. aaron			= DONE
		2. anastasia		= DONE
		3. christine		= DONE
		4. diana_ross		= DONE
	- Event
		1. 10year_reunion	= DONE
		2. 20year_reunion	= DONE
		3. brotherfield		= DONE
		4. christmas_dinner	= DONE
		5. lacasadepapel	= DONE
		6. music			= Fitur tidak ada
		7. oceandor			= DONE
		8. seminary			= DONE
	- Wedding
		1. dylan_rose		= Belum ada design nya
		2. emma_norman		= DONE
		3. jack_jane		= DONE
		4. liam_felicia		= DONE
		5. lucas_eli		= DONE
		6. natasha_bruce	= DONE
		7. peter_mary		= DONE
		8. steve_sharon		= DONE
		9. vicky_wanda		= DONE
		10. victor_karla	= DONE
	- Free
		1. anastasia		= Fitur tidak ada
		2. christine		= Fitur tidak ada
		3. diana_ross		= Fitur tidak ada
		4. dylan_rose		= Fitur tidak ada
		5. natasha_bruce	= Fitur tidak ada
		6. steve_sharon		= Fitur tidak ada


## Template bug
	- Birthday
		1. aaron			= DONE
		2. anastasia		= DONE
		3. christine		= DONE
		4. diana_ross		= DONE
	- Event
		1. 10year_reunion	= DONE
		2. 20year_reunion	= DONE
		3. brotherfield		= DONE
		4. christmas_dinner	= DONE
		5. lacasadepapel	= DONE
		6. music			= DONE
		7. oceandor			= DONE
		8. seminary			= DONE
	- Wedding
		1. dylan_rose		= DONE
		2. emma_norman		= DONE
		3. jack_jane		= DONE
		4. liam_felicia		= DONE
		5. lucas_eli		= DONE
		6. natasha_bruce	= DONE
		7. peter_mary		= DONE
		8. steve_sharon		= DONE
		9. vicky_wanda		= DONE
		10. victor_karla	= DONE
	- Free
		1. anastasia		= DONE
		2. christine		= DONE
		3. diana_ross		= DONE
		4. dylan_rose		= DONE
		5. natasha_bruce	= DONE
		6. steve_sharon		= DONE


## Template Navbar Preview
	- Birthday
		1. aaron			= DONE
		2. anastasia		= DONE
		3. christine		= DONE
		4. diana_ross		= DONE
	- Event
		1. 10year_reunion	= DONE
		2. 20year_reunion	= DONE
		3. brotherfield		= DONE
		4. christmas_dinner	= DONE
		5. lacasadepapel	= DONE
		6. music			= DONE
		7. oceandor			= DONE
		8. seminary			= DONE
	- Wedding
		1. dylan_rose		= DONE
		2. emma_norman		= DONE
		3. jack_jane		= DONE
		4. liam_felicia		= DONE
		5. lucas_eli		= DONE
		6. natasha_bruce	= DONE
		7. peter_mary		= DONE
		8. steve_sharon		= DONE
		9. vicky_wanda		= DONE
		10. victor_karla	= DONE
	- Free
		1. anastasia		= DONE
		2. christine		= DONE
		3. diana_ross		= DONE
		4. dylan_rose		= DONE
		5. natasha_bruce	= DONE
		6. steve_sharon		= DONE


## Template Form Input
	- Birthday
		1. aaron			= inputan tidak muncul
		2. anastasia		= inputan tidak muncul
		3. christine		= inputan tidak muncul
		4. diana_ross		= inputan tidak muncul
	- Event
		1. 10year_reunion	= link ngga bisa
		2. 20year_reunion	= link ngga bisa
		3. brotherfield		= link ngga bisa
		4. christmas_dinner	= link ngga bisa
		5. lacasadepapel	= link ngga bisa
		6. music			= link ngga bisa
		7. oceandor			= link ngga bisa
		8. seminary			= link ngga bisa
	- Wedding
		1. dylan_rose		= inputan tidak muncul
		2. emma_norman		= preview ngga tampil data yang udah diinput
		3. jack_jane		= inputan tidak muncul
		4. liam_felicia		= inputan tidak muncul
		5. lucas_eli		= preview error
		6. natasha_bruce	= preview error
		7. peter_mary		= preview error
		8. steve_sharon		= preview error
		9. vicky_wanda		= preview error
		10. victor_karla	= preview error
	- Free
		1. anastasia		= link ngga bisa
		2. christine		= link ngga bisa
		3. diana_ross		= link ngga bisa
		4. dylan_rose		= link ngga bisa
		5. natasha_bruce	= link ngga bisa
		6. steve_sharon		= link ngga bisa