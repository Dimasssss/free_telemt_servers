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

# Server Metrics 2026-03-14 03:23:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 157821.3 (43h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 613893
telemt_connections_bad_total 27966
telemt_handshake_timeouts_total 12931
telemt_upstream_connect_attempt_total 40365
telemt_upstream_connect_success_total 40162
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 40365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5541
telemt_me_reconnect_attempts_total 36575
telemt_me_reconnect_success_total 31894
telemt_me_reader_eof_total 34083
telemt_me_idle_close_by_peer_total 34082
telemt_me_route_drop_no_conn_total 200053
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 521664
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1725
telemt_desync_full_logged_total 591
telemt_desync_suppressed_total 1134
telemt_desync_frames_bucket_total{bucket="1_2"} 369
telemt_desync_frames_bucket_total{bucket="3_10"} 650
telemt_desync_frames_bucket_total{bucket="gt_10"} 706
telemt_pool_swap_total 144
telemt_me_writer_removed_unexpected_total 32389
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 31874
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 495
telemt_user_connections_total{user="hello"} 521555
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 15683543818 (14.61 GB)
telemt_user_octets_to_client{user="hello"} 255883145244 (238.31 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 157714.1 (43h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 311941
telemt_connections_bad_total 2265
telemt_handshake_timeouts_total 1944
telemt_upstream_connect_attempt_total 145598
telemt_upstream_connect_success_total 144438
telemt_upstream_connect_fail_total 1160
telemt_upstream_connect_attempts_per_request{bucket="1"} 145598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2417
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1160
telemt_me_keepalive_timeout_total 3837
telemt_me_reconnect_attempts_total 165223
telemt_me_reconnect_success_total 33247
telemt_me_reader_eof_total 38256
telemt_me_idle_close_by_peer_total 38256
telemt_me_route_drop_no_conn_total 98579
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 192666
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 37687
telemt_me_refill_failed_total 4118
telemt_me_writer_restored_same_endpoint_total 33230
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4440
telemt_user_connections_total{user="hello"} 295778
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 3098942627 (2.89 GB)
telemt_user_octets_to_client{user="hello"} 94879900259 (88.36 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 157677.8 (43h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 365158
telemt_connections_bad_total 2910
telemt_handshake_timeouts_total 34547
telemt_upstream_connect_attempt_total 41829
telemt_upstream_connect_success_total 41823
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 41829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22631
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3314
telemt_me_reconnect_attempts_total 35178
telemt_me_reconnect_success_total 33905
telemt_me_reader_eof_total 36439
telemt_me_idle_close_by_peer_total 36439
telemt_me_route_drop_no_conn_total 130392
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 315051
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
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
telemt_pool_swap_total 149
telemt_me_writer_removed_unexpected_total 34301
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 33884
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 396
telemt_user_connections_total{user="hello"} 314869
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 12641641412 (11.77 GB)
telemt_user_octets_to_client{user="hello"} 127532795100 (118.77 GB)
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 157653.4 (43h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 466430
telemt_connections_bad_total 15543
telemt_handshake_timeouts_total 4397
telemt_upstream_connect_attempt_total 71232
telemt_upstream_connect_success_total 60735
telemt_upstream_connect_fail_total 10497
telemt_upstream_connect_attempts_per_request{bucket="1"} 71232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23979
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10497
telemt_me_keepalive_timeout_total 5119
telemt_me_reconnect_attempts_total 139870
telemt_me_reconnect_success_total 33826
telemt_me_reader_eof_total 38138
telemt_me_idle_close_by_peer_total 38130
telemt_me_route_drop_no_conn_total 165467
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 395483
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1708
telemt_desync_full_logged_total 501
telemt_desync_suppressed_total 1207
telemt_desync_frames_bucket_total{bucket="1_2"} 400
telemt_desync_frames_bucket_total{bucket="3_10"} 646
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 37533
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 33816
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3707
telemt_user_connections_total{user="hello"} 414313
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 9112380123 (8.49 GB)
telemt_user_octets_to_client{user="hello"} 161132982948 (150.07 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 107825.0 (29h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179010
telemt_connections_bad_total 25870
telemt_handshake_timeouts_total 1571
telemt_upstream_connect_attempt_total 39066
telemt_upstream_connect_success_total 38706
telemt_upstream_connect_fail_total 360
telemt_upstream_connect_attempts_per_request{bucket="1"} 39066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19028
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 360
telemt_me_keepalive_timeout_total 2356
telemt_me_reconnect_attempts_total 41871
telemt_me_reconnect_success_total 28451
telemt_me_reader_eof_total 30449
telemt_me_idle_close_by_peer_total 30449
telemt_me_route_drop_no_conn_total 53047
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 141711
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 622
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 29128
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 28433
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 677
telemt_user_connections_total{user="hello"} 146477
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 2156612889 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 67294855271 (62.67 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 157609.5 (43h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 901658
telemt_connections_bad_total 28008
telemt_handshake_timeouts_total 25397
telemt_upstream_connect_attempt_total 32768
telemt_upstream_connect_success_total 32597
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 32768
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17294
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_timeout_total 3503
telemt_me_reconnect_attempts_total 29442
telemt_me_reconnect_success_total 24775
telemt_me_reader_eof_total 26548
telemt_me_idle_close_by_peer_total 26545
telemt_me_route_drop_no_conn_total 429843
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 843188
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 744
telemt_desync_full_logged_total 243
telemt_desync_suppressed_total 501
telemt_desync_frames_bucket_total{bucket="1_2"} 255
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 246
telemt_pool_swap_total 148
telemt_me_writer_removed_unexpected_total 25236
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 24768
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 461
telemt_user_connections_total{user="hello"} 815853
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 14332798200 (13.35 GB)
telemt_user_octets_to_client{user="hello"} 412833261988 (384.48 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 42
```