---
title: "Recolorization of GrayScale Images using GANs"
collection: research
custom: 'true'
custom_remark: "Course Project for the Course EE 673 (Machine Learning), Spring '23, IIT Ropar"
permalink: /projects/AudioDeepfake
excerpt: "This paper introduces the IndieFake Dataset (IFD), a comprehensive audio deepfake dataset featuring 27.12 hours of bonafide and deepfake audio from 50 Indian English speakers. Addressing the lack of South-Asian representation in existing datasets, IFD offers balanced data distribution and includes speaker-level characterization to enhance deepfake detection in diverse linguistic and cultural contexts."
date: 2024-09-06
venue: 'Under Review at ICASSP 2025'
---

<style>

/* Style the counter cards */
.card {
<!--   box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2); /* this adds the "card" effect */ -->
  padding: 16px;
<!--   text-align: center; -->
<!--   background-color: #f1f1f1; -->
}

a:link {
  text-decoration: none;
}
</style>

Advancements in audio deepfake technology offers benefits like AI assistants, better accessibility for speech impairments, and enhanced entertainment. However, it also poses significant risks to security, privacy, and trust in digital communications. Detecting and mitigating these threats requires comprehensive datasets. Existing datasets lack diverse ethnic accents, making them inadequate for many real-world scenarios. Consequently, models trained on these datasets struggle to detect audio deepfakes in diverse linguistic and cultural contexts such as in South-Asian countries. Ironically, there is a stark lack of South-Asian speaker samples in the existing datasets despite constituting a quarter of the worlds population. This work introduces the IndieFake Dataset (IFD), featuring 27.12 hours of bonafide and deepfake audio from 50 English speaking Indian speakers. IFD offers balanced data distribution and includes speaker-level characterization, absent in datasets like ASVspoof21(DF). We evaluated various baselines on IFD against existing ASVspoof21 (DF) and In-The-Wild (ITW) datasets. IFD outperforms ASVspoof21 (DF) and proves to be more challenging compared to benchmark ITW dataset. The dataset will be publicly available upon acceptance.  
