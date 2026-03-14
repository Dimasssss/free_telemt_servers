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

# Server Metrics 2026-03-14 10:21:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 182869.8 (50h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 711960
telemt_connections_bad_total 33527
telemt_handshake_timeouts_total 13841
telemt_upstream_connect_attempt_total 46570
telemt_upstream_connect_success_total 46335
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 46570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25004
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5973
telemt_me_reconnect_attempts_total 42138
telemt_me_reconnect_success_total 36825
telemt_me_reader_eof_total 39360
telemt_me_idle_close_by_peer_total 39359
telemt_me_route_drop_no_conn_total 235503
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 609570
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2414
telemt_desync_full_logged_total 808
telemt_desync_suppressed_total 1606
telemt_desync_frames_bucket_total{bucket="1_2"} 515
telemt_desync_frames_bucket_total{bucket="3_10"} 889
telemt_desync_frames_bucket_total{bucket="gt_10"} 1010
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 37386
telemt_me_refill_failed_total 159
telemt_me_writer_restored_same_endpoint_total 36805
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 561
telemt_user_connections_total{user="hello"} 609449
telemt_user_connections_current{user="hello"} 385
telemt_user_octets_from_client{user="hello"} 17368687810 (16.18 GB)
telemt_user_octets_to_client{user="hello"} 289679538876 (269.79 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 182763.5 (50h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 356338
telemt_connections_bad_total 2823
telemt_handshake_timeouts_total 3141
telemt_upstream_connect_attempt_total 153903
telemt_upstream_connect_success_total 152551
telemt_upstream_connect_fail_total 1351
telemt_upstream_connect_attempts_per_request{bucket="1"} 153902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38533
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2457
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1351
telemt_me_keepalive_timeout_total 5451
telemt_me_reconnect_attempts_total 188440
telemt_me_reconnect_success_total 40153
telemt_me_reader_eof_total 45851
telemt_me_idle_close_by_peer_total 45851
telemt_me_route_drop_no_conn_total 122407
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 233237
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 45
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
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 45168
telemt_me_refill_failed_total 4627
telemt_me_writer_restored_same_endpoint_total 40136
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5015
telemt_user_connections_total{user="hello"} 336341
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 3446133071 (3.21 GB)
telemt_user_octets_to_client{user="hello"} 107403216491 (100.03 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 182727.1 (50h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 413318
telemt_connections_bad_total 3261
telemt_handshake_timeouts_total 35770
telemt_upstream_connect_attempt_total 48508
telemt_upstream_connect_success_total 48499
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 48508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26240
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3804
telemt_me_reconnect_attempts_total 40668
telemt_me_reconnect_success_total 39364
telemt_me_reader_eof_total 42289
telemt_me_idle_close_by_peer_total 42289
telemt_me_route_drop_no_conn_total 150178
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 359701
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 136
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 171
telemt_me_writer_removed_unexpected_total 39837
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 39343
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 473
telemt_user_connections_total{user="hello"} 359433
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 13943558644 (12.99 GB)
telemt_user_octets_to_client{user="hello"} 158428996616 (147.55 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 182702.7 (50h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 521633
telemt_connections_bad_total 16710
telemt_handshake_timeouts_total 5225
telemt_upstream_connect_attempt_total 78809
telemt_upstream_connect_success_total 68141
telemt_upstream_connect_fail_total 10668
telemt_upstream_connect_attempts_per_request{bucket="1"} 78809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28011
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 351
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10668
telemt_me_keepalive_timeout_total 5629
telemt_me_reconnect_attempts_total 152323
telemt_me_reconnect_success_total 40026
telemt_me_reader_eof_total 44827
telemt_me_idle_close_by_peer_total 44819
telemt_me_route_drop_no_conn_total 189106
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 446431
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2011
telemt_desync_full_logged_total 595
telemt_desync_suppressed_total 1416
telemt_desync_frames_bucket_total{bucket="1_2"} 478
telemt_desync_frames_bucket_total{bucket="3_10"} 771
telemt_desync_frames_bucket_total{bucket="gt_10"} 762
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 43990
telemt_me_refill_failed_total 3501
telemt_me_writer_restored_same_endpoint_total 40016
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3964
telemt_user_connections_total{user="hello"} 465298
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 9983573471 (9.30 GB)
telemt_user_octets_to_client{user="hello"} 192793745840 (179.55 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 132874.3 (36h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221067
telemt_connections_bad_total 34125
telemt_handshake_timeouts_total 1981
telemt_upstream_connect_attempt_total 46743
telemt_upstream_connect_success_total 46283
telemt_upstream_connect_fail_total 460
telemt_upstream_connect_attempts_per_request{bucket="1"} 46743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22989
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 460
telemt_me_keepalive_timeout_total 2771
telemt_me_reconnect_attempts_total 50661
telemt_me_reconnect_success_total 34782
telemt_me_reader_eof_total 37215
telemt_me_idle_close_by_peer_total 37215
telemt_me_route_drop_no_conn_total 66966
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174145
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 759
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 572
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 361
telemt_desync_frames_bucket_total{bucket="gt_10"} 271
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 35598
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 34764
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 816
telemt_user_connections_total{user="hello"} 178902
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 2671747417 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 83808068719 (78.05 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 182659.1 (50h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1058090
telemt_connections_bad_total 36964
telemt_handshake_timeouts_total 26905
telemt_upstream_connect_attempt_total 38163
telemt_upstream_connect_success_total 37962
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 38163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19963
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_keepalive_timeout_total 4870
telemt_me_reconnect_attempts_total 33631
telemt_me_reconnect_success_total 28944
telemt_me_reader_eof_total 31026
telemt_me_idle_close_by_peer_total 31023
telemt_me_route_drop_no_conn_total 495260
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 980826
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 806
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 540
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 278
telemt_pool_swap_total 170
telemt_me_writer_removed_unexpected_total 29454
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 28937
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 953438
telemt_user_connections_current{user="hello"} 454
telemt_user_octets_from_client{user="hello"} 17896172872 (16.67 GB)
telemt_user_octets_to_client{user="hello"} 479522716076 (446.59 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 68
```