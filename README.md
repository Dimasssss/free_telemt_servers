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

# Server Metrics 2026-03-13 18:54:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 127267.0 (35h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 539211
telemt_connections_bad_total 11418
telemt_handshake_timeouts_total 12292
telemt_upstream_connect_attempt_total 32309
telemt_upstream_connect_success_total 32144
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 32309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17202
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 5037
telemt_me_reconnect_attempts_total 30036
telemt_me_reconnect_success_total 25388
telemt_me_reader_eof_total 27115
telemt_me_idle_close_by_peer_total 27114
telemt_me_route_drop_no_conn_total 176901
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 466714
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1495
telemt_desync_full_logged_total 515
telemt_desync_suppressed_total 980
telemt_desync_frames_bucket_total{bucket="1_2"} 327
telemt_desync_frames_bucket_total{bucket="3_10"} 548
telemt_desync_frames_bucket_total{bucket="gt_10"} 620
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 25816
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 25372
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 428
telemt_user_connections_total{user="hello"} 466658
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 8634725386 (8.04 GB)
telemt_user_octets_to_client{user="hello"} 220761586240 (205.60 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 127159.8 (35h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268954
telemt_connections_bad_total 1957
telemt_handshake_timeouts_total 1846
telemt_upstream_connect_attempt_total 120925
telemt_upstream_connect_success_total 120009
telemt_upstream_connect_fail_total 916
telemt_upstream_connect_attempts_per_request{bucket="1"} 120925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 90740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27346
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1923
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 916
telemt_me_keepalive_timeout_total 3387
telemt_me_reconnect_attempts_total 132254
telemt_me_reconnect_success_total 26071
telemt_me_reader_eof_total 30133
telemt_me_idle_close_by_peer_total 30133
telemt_me_route_drop_no_conn_total 83146
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167517
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 32
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
telemt_me_writer_removed_unexpected_total 29628
telemt_me_refill_failed_total 3313
telemt_me_writer_restored_same_endpoint_total 26054
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3557
telemt_user_connections_total{user="hello"} 254881
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 2632015365 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 77273384884 (71.97 GB)
telemt_user_msgs_from_client{user="hello"} 1371289
telemt_user_msgs_to_client{user="hello"} 7773396
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 127123.6 (35h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 315956
telemt_connections_bad_total 2630
telemt_handshake_timeouts_total 20460
telemt_upstream_connect_attempt_total 33840
telemt_upstream_connect_success_total 33835
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 33840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18122
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2748
telemt_me_reconnect_attempts_total 28663
telemt_me_reconnect_success_total 27429
telemt_me_reader_eof_total 29425
telemt_me_idle_close_by_peer_total 29425
telemt_me_route_drop_no_conn_total 112852
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 281806
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
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 27738
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 27409
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 309
telemt_user_connections_total{user="hello"} 281715
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 10388827536 (9.68 GB)
telemt_user_octets_to_client{user="hello"} 117689539068 (109.61 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 127099.1 (35h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 420852
telemt_connections_bad_total 15145
telemt_handshake_timeouts_total 3891
telemt_upstream_connect_attempt_total 61474
telemt_upstream_connect_success_total 51201
telemt_upstream_connect_fail_total 10273
telemt_upstream_connect_attempts_per_request{bucket="1"} 61474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18615
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 292
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10273
telemt_me_keepalive_timeout_total 4701
telemt_me_reconnect_attempts_total 115977
telemt_me_reconnect_success_total 25806
telemt_me_reader_eof_total 29361
telemt_me_idle_close_by_peer_total 29354
telemt_me_route_drop_no_conn_total 145464
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 352567
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1382
telemt_desync_full_logged_total 417
telemt_desync_suppressed_total 965
telemt_desync_frames_bucket_total{bucket="1_2"} 345
telemt_desync_frames_bucket_total{bucket="3_10"} 526
telemt_desync_frames_bucket_total{bucket="gt_10"} 511
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 28953
telemt_me_refill_failed_total 2812
telemt_me_writer_restored_same_endpoint_total 25796
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3147
telemt_user_connections_total{user="hello"} 371448
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 8431396683 (7.85 GB)
telemt_user_octets_to_client{user="hello"} 131814174908 (122.76 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 77270.7 (21h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129551
telemt_connections_bad_total 15947
telemt_handshake_timeouts_total 1413
telemt_upstream_connect_attempt_total 29930
telemt_upstream_connect_success_total 29649
telemt_upstream_connect_fail_total 281
telemt_upstream_connect_attempts_per_request{bucket="1"} 29930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14234
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 281
telemt_me_keepalive_timeout_total 1218
telemt_me_reconnect_attempts_total 34284
telemt_me_reconnect_success_total 20894
telemt_me_reader_eof_total 22402
telemt_me_idle_close_by_peer_total 22402
telemt_me_route_drop_no_conn_total 40469
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103066
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 540
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 417
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 275
telemt_desync_frames_bucket_total{bucket="gt_10"} 187
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 21505
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 20876
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 611
telemt_user_connections_total{user="hello"} 107961
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 1245712193 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 38005623779 (35.40 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 127055.7 (35h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 778298
telemt_connections_bad_total 24779
telemt_handshake_timeouts_total 24788
telemt_upstream_connect_attempt_total 26312
telemt_upstream_connect_success_total 26173
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 26312
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13902
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 3029
telemt_me_reconnect_attempts_total 24494
telemt_me_reconnect_success_total 19850
telemt_me_reader_eof_total 21304
telemt_me_idle_close_by_peer_total 21301
telemt_me_route_drop_no_conn_total 369938
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 729985
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 691
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 118
telemt_me_writer_removed_unexpected_total 20258
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 19843
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 408
telemt_user_connections_total{user="hello"} 702856
telemt_user_connections_current{user="hello"} 415
telemt_user_octets_from_client{user="hello"} 12253348068 (11.41 GB)
telemt_user_octets_to_client{user="hello"} 347393247476 (323.54 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 61
```