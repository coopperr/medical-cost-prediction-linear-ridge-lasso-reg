# medical-cost-prediction-linear-ridge-lasso-reg
sigorta fiyatı tahmini

#amaç
kişinin yaşı,cinsiyeti,vücut kitle endexi, bakmakal yükümlü olduğu çocuk sayısı, sigara içme surumu 
ve yaşadığı bölgeye göre sigorta fiyatı tahmini yapan model.

#kullanılan kütüphaneler 
--pandas--
--numpy--
--matplotlib--
--seaborn--
--scikit-learn--

## projenin bazı aşamaları
Dataset tanıma ve ön analiz,
Target değişkeninin (charges) sağa çarpık dağılımı nedeniyle MAD yöntemiyle aykırı değer analizi,
Log dönüşümü,
Pipeline yapısıyla ön işleme (OrdinalEncoder + StandardScaler),
Linear, Ridge ve Lasso Regression modelleriyle karşılaştırma
