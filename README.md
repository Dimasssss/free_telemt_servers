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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-18 15:17:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 23799.4 (6h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 892008
telemt_connections_bad_total 68647
telemt_handshake_timeouts_total 25035
telemt_upstream_connect_attempt_total 67373
telemt_upstream_connect_success_total 66400
telemt_upstream_connect_fail_total 973
telemt_upstream_connect_attempts_per_request{bucket="1"} 67373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4742
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 973
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 520068
telemt_me_reconnect_success_total 3200
telemt_me_reader_eof_total 3543
telemt_me_idle_close_by_peer_total 3541
telemt_me_route_drop_no_conn_total 482434
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 681720
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3115
telemt_desync_full_logged_total 1067
telemt_desync_suppressed_total 2048
telemt_desync_frames_bucket_total{bucket="1_2"} 865
telemt_desync_frames_bucket_total{bucket="3_10"} 1046
telemt_desync_frames_bucket_total{bucket="gt_10"} 1204
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3543
telemt_me_refill_failed_total 16834
telemt_me_writer_restored_same_endpoint_total 3094
telemt_me_writer_restored_fallback_total 106
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 343
telemt_user_connections_total{user="hello"} 739789
telemt_user_connections_current{user="hello"} 1734
telemt_user_octets_from_client{user="hello"} 10943233572 (10.19 GB)
telemt_user_octets_to_client{user="hello"} 196309419113 (182.83 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 527
telemt_user_unique_ips_recent_window{user="hello"} 244
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 4368.0 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 513372
telemt_connections_bad_total 26112
telemt_connections_current 3660
telemt_connections_me_current 3660
telemt_handshake_timeouts_total 9894
telemt_upstream_connect_attempt_total 700
telemt_upstream_connect_success_total 696
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 700
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 264
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 452
telemt_me_reconnect_success_total 444
telemt_me_reader_eof_total 350
telemt_me_idle_close_by_peer_total 349
telemt_me_route_drop_no_conn_total 549499
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 454959
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1127
telemt_desync_full_logged_total 334
telemt_desync_suppressed_total 793
telemt_desync_frames_bucket_total{bucket="1_2"} 254
telemt_desync_frames_bucket_total{bucket="3_10"} 452
telemt_desync_frames_bucket_total{bucket="gt_10"} 421
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 366
telemt_me_writer_restored_same_endpoint_total 442
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 454194
telemt_user_connections_current{user="hello"} 3660
telemt_user_octets_from_client{user="hello"} 4260087812 (3.97 GB)
telemt_user_octets_to_client{user="hello"} 114437152860 (106.58 GB)
telemt_user_unique_ips_current{user="hello"} 1163
telemt_user_unique_ips_recent_window{user="hello"} 494
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 4296.5 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 319456
telemt_connections_bad_total 19532
telemt_connections_current 2880
telemt_connections_me_current 2880
telemt_handshake_timeouts_total 6070
telemt_upstream_connect_attempt_total 567
telemt_upstream_connect_success_total 563
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 322
telemt_me_reconnect_success_total 318
telemt_me_reader_eof_total 320
telemt_me_idle_close_by_peer_total 320
telemt_me_route_drop_no_conn_total 197584
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 277987
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 870
telemt_desync_full_logged_total 251
telemt_desync_suppressed_total 619
telemt_desync_frames_bucket_total{bucket="1_2"} 191
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 373
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 329
telemt_me_writer_restored_same_endpoint_total 301
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 277966
telemt_user_connections_current{user="hello"} 2880
telemt_user_octets_from_client{user="hello"} 5075984972 (4.73 GB)
telemt_user_octets_to_client{user="hello"} 102850482056 (95.79 GB)
telemt_user_unique_ips_current{user="hello"} 924
telemt_user_unique_ips_recent_window{user="hello"} 407
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 5010.7 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 528609
telemt_connections_bad_total 5047
telemt_connections_current 2525
telemt_connections_me_current 2525
telemt_handshake_timeouts_total 7525
telemt_upstream_connect_attempt_total 809
telemt_upstream_connect_success_total 804
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 512
telemt_me_reconnect_success_total 504
telemt_me_reader_eof_total 479
telemt_me_idle_close_by_peer_total 478
telemt_me_route_drop_no_conn_total 999906
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 481812
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1463
telemt_desync_full_logged_total 366
telemt_desync_suppressed_total 1097
telemt_desync_frames_bucket_total{bucket="1_2"} 308
telemt_desync_frames_bucket_total{bucket="3_10"} 705
telemt_desync_frames_bucket_total{bucket="gt_10"} 450
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 485
telemt_me_writer_restored_same_endpoint_total 493
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 481787
telemt_user_connections_current{user="hello"} 2525
telemt_user_octets_from_client{user="hello"} 3213615344 (2.99 GB)
telemt_user_octets_to_client{user="hello"} 72748492492 (67.75 GB)
telemt_user_unique_ips_current{user="hello"} 787
telemt_user_unique_ips_recent_window{user="hello"} 347
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 23670.5 (6h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1947033
telemt_connections_bad_total 174479
telemt_handshake_timeouts_total 29693
telemt_upstream_connect_attempt_total 15811
telemt_upstream_connect_success_total 15783
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 15811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2226
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 808
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2987339
telemt_me_reconnect_success_total 2894
telemt_me_reader_eof_total 3029
telemt_me_idle_close_by_peer_total 3029
telemt_me_route_drop_no_conn_total 1983119
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1603573
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4581
telemt_desync_full_logged_total 1617
telemt_desync_suppressed_total 2964
telemt_desync_frames_bucket_total{bucket="1_2"} 749
telemt_desync_frames_bucket_total{bucket="3_10"} 1780
telemt_desync_frames_bucket_total{bucket="gt_10"} 2052
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2969
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 2779
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 1605366
telemt_user_connections_current{user="hello"} 3063
telemt_user_octets_from_client{user="hello"} 25855549799 (24.08 GB)
telemt_user_octets_to_client{user="hello"} 537120864961 (500.23 GB)
telemt_user_msgs_from_client{user="hello"} 89703
telemt_user_msgs_to_client{user="hello"} 269409
telemt_user_unique_ips_current{user="hello"} 978
telemt_user_unique_ips_recent_window{user="hello"} 435
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 4459.0 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96085
telemt_connections_bad_total 5317
telemt_connections_current 878
telemt_connections_me_current 878
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 903
telemt_upstream_connect_attempt_total 4825
telemt_upstream_connect_success_total 4818
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1976
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 330205
telemt_me_reconnect_success_total 748
telemt_me_reader_eof_total 669
telemt_me_idle_close_by_peer_total 669
telemt_me_route_drop_no_conn_total 55183
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81733
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 176
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 670
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 737
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 85499
telemt_user_connections_current{user="hello"} 878
telemt_user_octets_from_client{user="hello"} 1475245389 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 15422453957 (14.36 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 3529.8 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 250180
telemt_connections_bad_total 11313
telemt_connections_current 2648
telemt_connections_me_current 2648
telemt_handshake_timeouts_total 2295
telemt_upstream_connect_attempt_total 639
telemt_upstream_connect_success_total 639
telemt_upstream_connect_attempts_per_request{bucket="1"} 639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 274
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 14726
telemt_me_reconnect_success_total 436
telemt_me_reader_eof_total 330
telemt_me_idle_close_by_peer_total 330
telemt_me_route_drop_no_conn_total 185187
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 213080
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 504
telemt_desync_full_logged_total 179
telemt_desync_suppressed_total 325
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 345
telemt_me_refill_failed_total 703
telemt_me_writer_restored_same_endpoint_total 375
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 213533
telemt_user_connections_current{user="hello"} 2648
telemt_user_octets_from_client{user="hello"} 2229069900 (2.08 GB)
telemt_user_octets_to_client{user="hello"} 79152928744 (73.72 GB)
telemt_user_unique_ips_current{user="hello"} 818
telemt_user_unique_ips_recent_window{user="hello"} 339
```