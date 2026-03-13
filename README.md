# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-13 18:44:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 126655.6 (35h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 535773
telemt_connections_bad_total 10980
telemt_handshake_timeouts_total 12231
telemt_upstream_connect_attempt_total 31765
telemt_upstream_connect_success_total 31610
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 31765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17116
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3499
telemt_me_reconnect_attempts_total 29924
telemt_me_reconnect_success_total 25282
telemt_me_reader_eof_total 27003
telemt_me_idle_close_by_peer_total 27002
telemt_me_route_drop_no_conn_total 175647
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 464290
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1475
telemt_desync_full_logged_total 511
telemt_desync_suppressed_total 964
telemt_desync_frames_bucket_total{bucket="1_2"} 323
telemt_desync_frames_bucket_total{bucket="3_10"} 543
telemt_desync_frames_bucket_total{bucket="gt_10"} 609
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 25707
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 25266
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 425
telemt_user_connections_total{user="hello"} 463859
telemt_user_connections_current{user="hello"} 266
telemt_user_octets_from_client{user="hello"} 8522354368 (7.94 GB)
telemt_user_octets_to_client{user="hello"} 220219670720 (205.10 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 126548.3 (35h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266659
telemt_connections_bad_total 1954
telemt_handshake_timeouts_total 1843
telemt_upstream_connect_attempt_total 118793
telemt_upstream_connect_success_total 117931
telemt_upstream_connect_fail_total 862
telemt_upstream_connect_attempts_per_request{bucket="1"} 118793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 88952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1837
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 862
telemt_me_keepalive_timeout_total 1540
telemt_me_reconnect_attempts_total 131456
telemt_me_reconnect_success_total 26033
telemt_me_reader_eof_total 30081
telemt_me_idle_close_by_peer_total 30081
telemt_me_route_drop_no_conn_total 83126
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167315
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 29551
telemt_me_refill_failed_total 3290
telemt_me_writer_restored_same_endpoint_total 26016
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3518
telemt_user_connections_total{user="hello"} 252686
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 2621113679 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 77027735246 (71.74 GB)
telemt_user_msgs_from_client{user="hello"} 1346565
telemt_user_msgs_to_client{user="hello"} 7680087
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 126511.7 (35h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 314405
telemt_connections_bad_total 2630
telemt_handshake_timeouts_total 20054
telemt_upstream_connect_attempt_total 33681
telemt_upstream_connect_success_total 33676
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 33681
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18042
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2729
telemt_me_reconnect_attempts_total 28548
telemt_me_reconnect_success_total 27315
telemt_me_reader_eof_total 29297
telemt_me_idle_close_by_peer_total 29297
telemt_me_route_drop_no_conn_total 112221
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 280709
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 27622
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 27295
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 307
telemt_user_connections_total{user="hello"} 280618
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 10365749988 (9.65 GB)
telemt_user_octets_to_client{user="hello"} 116454600840 (108.46 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 126487.2 (35h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 419186
telemt_connections_bad_total 15145
telemt_handshake_timeouts_total 3889
telemt_upstream_connect_attempt_total 61209
telemt_upstream_connect_success_total 50941
telemt_upstream_connect_fail_total 10267
telemt_upstream_connect_attempts_per_request{bucket="1"} 61208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18462
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 288
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10267
telemt_me_keepalive_timeout_total 4688
telemt_me_reconnect_attempts_total 115251
telemt_me_reconnect_success_total 25591
telemt_me_reader_eof_total 29126
telemt_me_idle_close_by_peer_total 29119
telemt_me_route_drop_no_conn_total 144805
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 350952
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1375
telemt_desync_full_logged_total 412
telemt_desync_suppressed_total 963
telemt_desync_frames_bucket_total{bucket="1_2"} 340
telemt_desync_frames_bucket_total{bucket="3_10"} 525
telemt_desync_frames_bucket_total{bucket="gt_10"} 510
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 28718
telemt_me_refill_failed_total 2796
telemt_me_writer_restored_same_endpoint_total 25581
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3127
telemt_user_connections_total{user="hello"} 369833
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 8422865219 (7.84 GB)
telemt_user_octets_to_client{user="hello"} 131507133484 (122.48 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 76658.8 (21h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128396
telemt_connections_bad_total 15841
telemt_handshake_timeouts_total 1408
telemt_upstream_connect_attempt_total 29829
telemt_upstream_connect_success_total 29548
telemt_upstream_connect_fail_total 281
telemt_upstream_connect_attempts_per_request{bucket="1"} 29829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 281
telemt_me_keepalive_timeout_total 1218
telemt_me_reconnect_attempts_total 34183
telemt_me_reconnect_success_total 20793
telemt_me_reader_eof_total 22297
telemt_me_idle_close_by_peer_total 22297
telemt_me_route_drop_no_conn_total 40127
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102075
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 500
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 386
telemt_desync_frames_bucket_total{bucket="1_2"} 73
telemt_desync_frames_bucket_total{bucket="3_10"} 265
telemt_desync_frames_bucket_total{bucket="gt_10"} 162
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 21402
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 20775
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 609
telemt_user_connections_total{user="hello"} 106971
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 1235630057 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 36318168751 (33.82 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 126443.5 (35h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 774487
telemt_connections_bad_total 24775
telemt_handshake_timeouts_total 24745
telemt_upstream_connect_attempt_total 26211
telemt_upstream_connect_success_total 26072
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 26211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13837
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 3013
telemt_me_reconnect_attempts_total 24436
telemt_me_reconnect_success_total 19792
telemt_me_reader_eof_total 21241
telemt_me_idle_close_by_peer_total 21238
telemt_me_route_drop_no_conn_total 368110
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 726614
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 689
telemt_desync_full_logged_total 224
telemt_desync_suppressed_total 465
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 224
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 20199
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 19785
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 407
telemt_user_connections_total{user="hello"} 699486
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 12235090412 (11.39 GB)
telemt_user_octets_to_client{user="hello"} 346286902368 (322.50 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 67
```