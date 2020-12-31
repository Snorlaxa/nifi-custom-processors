# nifi-custom-processors
自定义Apache Nifi组件，尝试解决原生standard组件存在的问题，增强一些组件的功能，以助于更好地实现业务场景

+ 尝试解决CaptureChangeMySQL oom隐患

+ PutDatabaseRecord的upsert功能增强，包括增加对mysql的支持和on conflict do nothing特性
