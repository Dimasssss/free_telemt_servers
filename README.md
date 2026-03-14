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

# Server Metrics 2026-03-14 02:37:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 155070.9 (43h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 604102
telemt_connections_bad_total 22748
telemt_handshake_timeouts_total 12917
telemt_upstream_connect_attempt_total 39627
telemt_upstream_connect_success_total 39430
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 39627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21235
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5512
telemt_me_reconnect_attempts_total 35972
telemt_me_reconnect_success_total 31293
telemt_me_reader_eof_total 33438
telemt_me_idle_close_by_peer_total 33437
telemt_me_route_drop_no_conn_total 198111
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 517243
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1679
telemt_desync_full_logged_total 579
telemt_desync_suppressed_total 1100
telemt_desync_frames_bucket_total{bucket="1_2"} 357
telemt_desync_frames_bucket_total{bucket="3_10"} 634
telemt_desync_frames_bucket_total{bucket="gt_10"} 688
telemt_pool_swap_total 141
telemt_me_writer_removed_unexpected_total 31782
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 31277
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 489
telemt_user_connections_total{user="hello"} 517134
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 15634773462 (14.56 GB)
telemt_user_octets_to_client{user="hello"} 254301527416 (236.84 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 154963.6 (43h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 309308
telemt_connections_bad_total 2249
telemt_handshake_timeouts_total 1941
telemt_upstream_connect_attempt_total 144528
telemt_upstream_connect_success_total 143380
telemt_upstream_connect_fail_total 1148
telemt_upstream_connect_attempts_per_request{bucket="1"} 144528
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 107635
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33328
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2417
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1148
telemt_me_keepalive_timeout_total 3818
telemt_me_reconnect_attempts_total 163718
telemt_me_reconnect_success_total 32319
telemt_me_reader_eof_total 37259
telemt_me_idle_close_by_peer_total 37259
telemt_me_route_drop_no_conn_total 97860
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 190158
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 39
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
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 36726
telemt_me_refill_failed_total 4100
telemt_me_writer_restored_same_endpoint_total 32302
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4407
telemt_user_connections_total{user="hello"} 293270
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 3060705943 (2.85 GB)
telemt_user_octets_to_client{user="hello"} 92262280971 (85.93 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 154927.1 (43h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 362034
telemt_connections_bad_total 2829
telemt_handshake_timeouts_total 33628
telemt_upstream_connect_attempt_total 41134
telemt_upstream_connect_success_total 41128
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 41134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22277
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3297
telemt_me_reconnect_attempts_total 34612
telemt_me_reconnect_success_total 33343
telemt_me_reader_eof_total 35827
telemt_me_idle_close_by_peer_total 35827
telemt_me_route_drop_no_conn_total 129353
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 313011
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
telemt_pool_swap_total 146
telemt_me_writer_removed_unexpected_total 33734
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 33323
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 391
telemt_user_connections_total{user="hello"} 312841
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 12629647916 (11.76 GB)
telemt_user_octets_to_client{user="hello"} 127218172756 (118.48 GB)
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 154902.8 (43h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 463049
telemt_connections_bad_total 15378
telemt_handshake_timeouts_total 4385
telemt_upstream_connect_attempt_total 70374
telemt_upstream_connect_success_total 59896
telemt_upstream_connect_fail_total 10477
telemt_upstream_connect_attempts_per_request{bucket="1"} 70373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23568
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 325
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10477
telemt_me_keepalive_timeout_total 5109
telemt_me_reconnect_attempts_total 139168
telemt_me_reconnect_success_total 33125
telemt_me_reader_eof_total 37388
telemt_me_idle_close_by_peer_total 37380
telemt_me_route_drop_no_conn_total 163996
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 392670
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
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 36830
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 33115
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3705
telemt_user_connections_total{user="hello"} 411503
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 9086696919 (8.46 GB)
telemt_user_octets_to_client{user="hello"} 158999449468 (148.08 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 105074.4 (29h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175377
telemt_connections_bad_total 25371
telemt_handshake_timeouts_total 1564
telemt_upstream_connect_attempt_total 38270
telemt_upstream_connect_success_total 37917
telemt_upstream_connect_fail_total 353
telemt_upstream_connect_attempts_per_request{bucket="1"} 38270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18590
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 353
telemt_me_keepalive_timeout_total 2338
telemt_me_reconnect_attempts_total 41211
telemt_me_reconnect_success_total 27793
telemt_me_reader_eof_total 29739
telemt_me_idle_close_by_peer_total 29739
telemt_me_route_drop_no_conn_total 51968
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 138629
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 619
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 28462
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 27775
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 669
telemt_user_connections_total{user="hello"} 143408
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 2035649841 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 65000873679 (60.54 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 154858.9 (43h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 892356
telemt_connections_bad_total 27748
telemt_handshake_timeouts_total 25354
telemt_upstream_connect_attempt_total 32103
telemt_upstream_connect_success_total 31931
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 32102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16944
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_timeout_total 3499
telemt_me_reconnect_attempts_total 28929
telemt_me_reconnect_success_total 24261
telemt_me_reader_eof_total 25997
telemt_me_idle_close_by_peer_total 25994
telemt_me_route_drop_no_conn_total 425385
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 834239
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 708
telemt_desync_full_logged_total 231
telemt_desync_suppressed_total 477
telemt_desync_frames_bucket_total{bucket="1_2"} 253
telemt_desync_frames_bucket_total{bucket="3_10"} 231
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 144
telemt_me_writer_removed_unexpected_total 24722
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 24254
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 461
telemt_user_connections_total{user="hello"} 806996
telemt_user_connections_current{user="hello"} 266
telemt_user_octets_from_client{user="hello"} 14269018824 (13.29 GB)
telemt_user_octets_to_client{user="hello"} 409903662372 (381.75 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 32
```