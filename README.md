# Project Background:

Laptops have become essential tools for a wide range of activities, from gaming and graphic design to remote work and education. With the vast number of brands and models available, understanding the factors that influence laptop pricing is crucial for informed decision-making.

This project aims to make laptop pricing easier to understand by looking at key features that affect value, like RAM, CPU speed, GPU type, screen size, and operating system. By analyzing these features, we hope to find trends and insights that help consumers choose the best laptop for their needs and give businesses a better idea of what customers prefer. 

By showing how each feature impacts price, this project will help everyone understand what makes different laptop models worth their price.

The code for exploratory data analysis can be accessed [here](/Exploratory_analysis.ipynb).

# Data Structures

The laptop price dataset consists of a single table that contains various attributes related to different laptop models.

![laptop data structure](/Laptop%20data%20structure.jpg)

## Executive Summary:

**Overview of Findings** 

Brands like Dell, Lenovo, and HP dominate the market, each offering more than 250 models, while Apple has a smaller, more premium range with only 21 models. Windows 10 is the most common operating system, found in over 1,000 laptops. Only around 15% of laptops feature a touchscreen, and 8GB of RAM is the most common memory size, with more than 600 models featuring it.




### Average laptop prices based on key features:

Among the various operating systems, macOS laptops stand out as the most expensive, averaging €1,749. In contrast, Windows 10 laptops are more accessible, with an average price of €1,180. Windows 7 and Mac OS X models, despite being less common, often exceed €1,250.

![OS price](/image.png)

When it comes to specific use cases, workstation laptops take the lead, averaging €2,280, followed closely by gaming laptops at €1,731. For those seeking more economical options, notebooks present a budget-friendly alternative, averaging just €788.

![laptop type price](/image-1.png)

The choice of processor significantly influences price. Laptops powered by Intel CPUs average €1,163, while those with AMD processors are more affordable at €560. In the graphics department, Nvidia GPUs command higher prices, averaging €1,496, compared to Intel GPU laptops, which average €1,020.


![CPU company price](/image-2.png)

Laptops with touchscreens average €1,453, and the premium 4K Ultra HD models can cost over €2,000, appealing to consumers who value high-resolution displays for gaming or design work.

Non-touchscreen models are more budget-friendly, averaging €1,079, while Retina display models come in at €1,657.

Laptops with higher screen resolutions, such as Quad HD+ and 4K Ultra HD, can cost significantly more, with 4K models exceeding €2,500. Although touchscreens add to the price, the difference is minimal for Full HD models.

![Touchscreen price](/image-3.png)


Devices with 512 GB primary storage and 1024 GB secondary storage can command prices up to €3500, appealing to users who need large capacity for heavy tasks or multimedia storage. 

On the other hand, smaller storage combinations, such as 8 GB primary storage with no secondary storage, are more budget-friendly, priced under €500, making them ideal for basic computing needs or entry-level users.

Storage size also plays a vital role in pricing. Laptops with 512GB primary storage and 1TB secondary storage can reach prices up to €3,500

![primary storage price](/image-8.png)

Devices equipped with a Retina display and 1200 GB of primary storage have prices reaching up to €2000, offering a premium visual experience for users who prioritize display quality alongside storage. 

On the other hand, devices without a Retina display but with a larger 2TB primary storage can cost as much as €3000, catering to users who prioritize storage over screen clarity. 

Interestingly, devices without a Retina display generally start at lower prices, around €500, making them more accessible, while those with a Retina display typically range between €500 and €1500 for entry-level models, reflecting the added value of enhanced display quality. 

This contrast shows how display and storage features create distinct pricing tiers, allowing users to choose based on their specific needs, whether for enhanced visuals or greater storage.

![Retina display pricing](/image-9.png)

Devices with Windows 10 and touchscreen have the highest prices, reaching up to €2000, while those with No OS or Chrome OS and no touchscreen are priced significantly lower, around €500.

![os vs touchscreen price](/image-10.png)

This scatter plot visualizes the relationship between CPU frequency (GHz) and RAM (GB) across different operating systems. Most devices cluster between 1.5 GHz to 2.5 GHz CPU frequency, with RAM typically ranging from 4 GB to 16 GB. 

A few outliers show RAM exceeding 60 GB, indicating high-performance machines. Devices running Windows 10 and Windows 7 appear frequently, suggesting they are common configurations, while No OS devices tend to have lower CPU frequencies and RAM. 

The chart highlights how most devices balance between moderate CPU power and RAM, catering to typical user needs.

![Scatter plot](/image-11.png)


### Feature Analysis:

Dell, Lenovo, HP, Asus, and Acer lead the laptop market. Dell, Lenovo, and HP each boast more than 250 models, while Asus and Acer offer over 100 models each, demonstrating their commitment to catering to various consumer preferences.

![brand features](/image-4.png)

Intel CPUs dominate, powering 95% of laptops, while AMD CPUs hold a modest share of 4.71%.

![cpu company features](/image-5.png)

When it comes to graphics, Nvidia GPUs are utilized in 31% of laptops, with Intel GPUs found in 55%.

![GPU company features](/image-6.png)

The 72% of laptops lack an IPS panel, indicating a potential area for improvement in display quality. Interestingly, the 15.6-inch screen size is the most common, with over 640 models offering this configuration, appealing to a broad audience.

![IPS panel feature](/image-7.png)


# Recommendations:

- Brands with fewer models, like Samsung and Microsoft, should consider expanding their premium range to compete in higher-priced segments.

- Since most users prefer 8GB or 16GB RAM, manufacturers should ensure these options remain affordable and widely available.

- As touchscreens increase prices, brands should offer more models with this feature, especially for high-end buyers.

- Laptops with AMD processors and non-touchscreen displays have lower prices, making them attractive to budget-conscious buyers. Expanding this segment could help reach a larger market.

- Workstation laptops, though fewer in number, have the highest prices. Offering more powerful configurations with Nvidia GPUs can attract professionals and gamers willing to pay a premium.