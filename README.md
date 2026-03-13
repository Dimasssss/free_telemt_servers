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

# Server Metrics 2026-03-13 22:13:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 139181.7 (38h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 576160
telemt_connections_bad_total 17301
telemt_handshake_timeouts_total 12805
telemt_upstream_connect_attempt_total 35319
telemt_upstream_connect_success_total 35142
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 35319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18897
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5113
telemt_me_reconnect_attempts_total 32467
telemt_me_reconnect_success_total 27807
telemt_me_reader_eof_total 29696
telemt_me_idle_close_by_peer_total 29695
telemt_me_route_drop_no_conn_total 190218
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 495576
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1585
telemt_desync_full_logged_total 537
telemt_desync_suppressed_total 1048
telemt_desync_frames_bucket_total{bucket="1_2"} 340
telemt_desync_frames_bucket_total{bucket="3_10"} 591
telemt_desync_frames_bucket_total{bucket="gt_10"} 654
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 28267
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 27791
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 460
telemt_user_connections_total{user="hello"} 495470
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 14875909750 (13.85 GB)
telemt_user_octets_to_client{user="hello"} 244424160780 (227.64 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 139074.9 (38h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 294247
telemt_connections_bad_total 2139
telemt_handshake_timeouts_total 1920
telemt_upstream_connect_attempt_total 139154
telemt_upstream_connect_success_total 138134
telemt_upstream_connect_fail_total 1020
telemt_upstream_connect_attempts_per_request{bucket="1"} 139154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30085
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1020
telemt_me_keepalive_timeout_total 3701
telemt_me_reconnect_attempts_total 147225
telemt_me_reconnect_success_total 27873
telemt_me_reader_eof_total 32348
telemt_me_idle_close_by_peer_total 32348
telemt_me_route_drop_no_conn_total 87632
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175885
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 36
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
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 31864
telemt_me_refill_failed_total 3724
telemt_me_writer_restored_same_endpoint_total 27856
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3991
telemt_user_connections_total{user="hello"} 278998
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 2950754407 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 86169402323 (80.25 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 139040.5 (38h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 341896
telemt_connections_bad_total 2658
telemt_handshake_timeouts_total 28094
telemt_upstream_connect_attempt_total 36999
telemt_upstream_connect_success_total 36994
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 36999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17046
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19906
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2852
telemt_me_reconnect_attempts_total 31260
telemt_me_reconnect_success_total 30013
telemt_me_reader_eof_total 32205
telemt_me_idle_close_by_peer_total 32205
telemt_me_route_drop_no_conn_total 121450
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 299142
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
telemt_pool_swap_total 128
telemt_me_writer_removed_unexpected_total 30354
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 29993
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 341
telemt_user_connections_total{user="hello"} 299043
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 12348973828 (11.50 GB)
telemt_user_octets_to_client{user="hello"} 123966996028 (115.45 GB)
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 139014.2 (38h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 446304
telemt_connections_bad_total 15279
telemt_handshake_timeouts_total 4234
telemt_upstream_connect_attempt_total 64323
telemt_upstream_connect_success_total 53953
telemt_upstream_connect_fail_total 10370
telemt_upstream_connect_attempts_per_request{bucket="1"} 64323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 304
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10370
telemt_me_keepalive_timeout_total 4771
telemt_me_reconnect_attempts_total 130449
telemt_me_reconnect_success_total 27980
telemt_me_reader_eof_total 31967
telemt_me_idle_close_by_peer_total 31960
telemt_me_route_drop_no_conn_total 155870
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 376808
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1596
telemt_desync_full_logged_total 471
telemt_desync_suppressed_total 1125
telemt_desync_frames_bucket_total{bucket="1_2"} 379
telemt_desync_frames_bucket_total{bucket="3_10"} 607
telemt_desync_frames_bucket_total{bucket="gt_10"} 610
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 31534
telemt_me_refill_failed_total 3196
telemt_me_writer_restored_same_endpoint_total 27970
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3554
telemt_user_connections_total{user="hello"} 395650
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 8971736691 (8.36 GB)
telemt_user_octets_to_client{user="hello"} 151164424412 (140.78 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 89185.8 (24h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150248
telemt_connections_bad_total 22272
telemt_handshake_timeouts_total 1536
telemt_upstream_connect_attempt_total 33126
telemt_upstream_connect_success_total 32815
telemt_upstream_connect_fail_total 311
telemt_upstream_connect_attempts_per_request{bucket="1"} 33126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15870
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 311
telemt_me_keepalive_timeout_total 1304
telemt_me_reconnect_attempts_total 36865
telemt_me_reconnect_success_total 23468
telemt_me_reader_eof_total 25134
telemt_me_idle_close_by_peer_total 25134
telemt_me_route_drop_no_conn_total 46093
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116844
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 616
telemt_desync_full_logged_total 144
telemt_desync_suppressed_total 472
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 303
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 24109
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 23450
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 641
telemt_user_connections_total{user="hello"} 121738
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 1411546469 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 57599155403 (53.64 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 138970.3 (38h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 839184
telemt_connections_bad_total 27132
telemt_handshake_timeouts_total 25122
telemt_upstream_connect_attempt_total 28595
telemt_upstream_connect_success_total 28445
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 28595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13294
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15112
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_keepalive_timeout_total 3125
telemt_me_reconnect_attempts_total 26198
telemt_me_reconnect_success_total 21546
telemt_me_reader_eof_total 23109
telemt_me_idle_close_by_peer_total 23106
telemt_me_route_drop_no_conn_total 400105
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 785375
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 693
telemt_desync_full_logged_total 226
telemt_desync_suppressed_total 467
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 130
telemt_me_writer_removed_unexpected_total 21975
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 21539
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 429
telemt_user_connections_total{user="hello"} 758230
telemt_user_connections_current{user="hello"} 282
telemt_user_octets_from_client{user="hello"} 13130447016 (12.23 GB)
telemt_user_octets_to_client{user="hello"} 377238742816 (351.33 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 40
```