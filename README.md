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

# Server Metrics 2026-03-14 11:47:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 188057.9 (52h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 740766
telemt_connections_bad_total 34611
telemt_handshake_timeouts_total 14386
telemt_upstream_connect_attempt_total 47791
telemt_upstream_connect_success_total 47555
telemt_upstream_connect_fail_total 236
telemt_upstream_connect_attempts_per_request{bucket="1"} 47791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25637
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 236
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6326
telemt_me_reconnect_attempts_total 43586
telemt_me_reconnect_success_total 37820
telemt_me_reader_eof_total 40437
telemt_me_idle_close_by_peer_total 40436
telemt_me_route_drop_no_conn_total 244378
telemt_me_route_drop_channel_closed_total 40
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 635616
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2679
telemt_desync_full_logged_total 893
telemt_desync_suppressed_total 1786
telemt_desync_frames_bucket_total{bucket="1_2"} 556
telemt_desync_frames_bucket_total{bucket="3_10"} 1005
telemt_desync_frames_bucket_total{bucket="gt_10"} 1118
telemt_pool_swap_total 170
telemt_me_writer_removed_unexpected_total 38405
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 37800
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 585
telemt_user_connections_total{user="hello"} 635516
telemt_user_connections_current{user="hello"} 437
telemt_user_octets_from_client{user="hello"} 17677807022 (16.46 GB)
telemt_user_octets_to_client{user="hello"} 305785268260 (284.78 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 187950.7 (52h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 367767
telemt_connections_bad_total 2837
telemt_handshake_timeouts_total 3307
telemt_upstream_connect_attempt_total 155772
telemt_upstream_connect_success_total 154388
telemt_upstream_connect_fail_total 1384
telemt_upstream_connect_attempts_per_request{bucket="1"} 155772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39776
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2478
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1384
telemt_me_keepalive_timeout_total 5693
telemt_me_reconnect_attempts_total 194972
telemt_me_reconnect_success_total 41720
telemt_me_reader_eof_total 47588
telemt_me_idle_close_by_peer_total 47588
telemt_me_route_drop_no_conn_total 127187
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 244143
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 46
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
telemt_me_writer_removed_unexpected_total 46906
telemt_me_refill_failed_total 4781
telemt_me_writer_restored_same_endpoint_total 41702
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5186
telemt_user_connections_total{user="hello"} 347240
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 3532472939 (3.29 GB)
telemt_user_octets_to_client{user="hello"} 111988892711 (104.30 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 187914.4 (52h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 425091
telemt_connections_bad_total 3311
telemt_handshake_timeouts_total 36472
telemt_upstream_connect_attempt_total 50148
telemt_upstream_connect_success_total 50139
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 50148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27014
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4282
telemt_me_reconnect_attempts_total 42002
telemt_me_reconnect_success_total 40681
telemt_me_reader_eof_total 43704
telemt_me_idle_close_by_peer_total 43704
telemt_me_route_drop_no_conn_total 155236
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 370098
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 145
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 78
telemt_pool_swap_total 175
telemt_me_writer_removed_unexpected_total 41170
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 40660
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 489
telemt_user_connections_total{user="hello"} 369858
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 15168527910 (14.13 GB)
telemt_user_octets_to_client{user="hello"} 162237572771 (151.10 GB)
telemt_user_msgs_from_client{user="hello"} 166
telemt_user_msgs_to_client{user="hello"} 712
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 187890.2 (52h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 538660
telemt_connections_bad_total 16770
telemt_handshake_timeouts_total 5292
telemt_upstream_connect_attempt_total 80449
telemt_upstream_connect_success_total 69748
telemt_upstream_connect_fail_total 10701
telemt_upstream_connect_attempts_per_request{bucket="1"} 80449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28800
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 382
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10701
telemt_me_keepalive_timeout_total 5834
telemt_me_reconnect_attempts_total 155998
telemt_me_reconnect_success_total 41356
telemt_me_reader_eof_total 46263
telemt_me_idle_close_by_peer_total 46255
telemt_me_route_drop_no_conn_total 195315
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 462274
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2109
telemt_desync_full_logged_total 621
telemt_desync_suppressed_total 1488
telemt_desync_frames_bucket_total{bucket="1_2"} 494
telemt_desync_frames_bucket_total{bucket="3_10"} 798
telemt_desync_frames_bucket_total{bucket="gt_10"} 817
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 45412
telemt_me_refill_failed_total 3574
telemt_me_writer_restored_same_endpoint_total 41346
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4056
telemt_user_connections_total{user="hello"} 481140
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 10171443327 (9.47 GB)
telemt_user_octets_to_client{user="hello"} 196055082216 (182.59 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 138061.5 (38h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233667
telemt_connections_bad_total 37241
telemt_handshake_timeouts_total 2142
telemt_upstream_connect_attempt_total 48473
telemt_upstream_connect_success_total 47987
telemt_upstream_connect_fail_total 486
telemt_upstream_connect_attempts_per_request{bucket="1"} 48473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23929
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23894
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 486
telemt_me_keepalive_timeout_total 3111
telemt_me_reconnect_attempts_total 52102
telemt_me_reconnect_success_total 36213
telemt_me_reader_eof_total 38724
telemt_me_idle_close_by_peer_total 38724
telemt_me_route_drop_no_conn_total 70770
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183153
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 789
telemt_desync_full_logged_total 193
telemt_desync_suppressed_total 596
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 287
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 37049
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 36195
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 836
telemt_user_connections_total{user="hello"} 187909
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 2747131577 (2.56 GB)
telemt_user_octets_to_client{user="hello"} 86374619779 (80.44 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 187846.2 (52h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1094975
telemt_connections_bad_total 37535
telemt_handshake_timeouts_total 27147
telemt_upstream_connect_attempt_total 39193
telemt_upstream_connect_success_total 38988
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 39193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20486
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_timeout_total 5181
telemt_me_reconnect_attempts_total 34395
telemt_me_reconnect_success_total 29701
telemt_me_reader_eof_total 31847
telemt_me_idle_close_by_peer_total 31844
telemt_me_route_drop_no_conn_total 514221
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1015478
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 809
telemt_desync_full_logged_total 268
telemt_desync_suppressed_total 541
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 175
telemt_me_writer_removed_unexpected_total 30224
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 29694
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 523
telemt_user_connections_total{user="hello"} 988063
telemt_user_connections_current{user="hello"} 447
telemt_user_octets_from_client{user="hello"} 21155804508 (19.70 GB)
telemt_user_octets_to_client{user="hello"} 494776645524 (460.80 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 62
```