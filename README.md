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

# Server Metrics 2026-03-14 06:01:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 167293.3 (46h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 643773
telemt_connections_bad_total 32303
telemt_handshake_timeouts_total 13000
telemt_upstream_connect_attempt_total 42618
telemt_upstream_connect_success_total 42402
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 42618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22901
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5578
telemt_me_reconnect_attempts_total 38383
telemt_me_reconnect_success_total 33694
telemt_me_reader_eof_total 36027
telemt_me_idle_close_by_peer_total 36026
telemt_me_route_drop_no_conn_total 210678
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 546020
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1960
telemt_desync_full_logged_total 670
telemt_desync_suppressed_total 1290
telemt_desync_frames_bucket_total{bucket="1_2"} 423
telemt_desync_frames_bucket_total{bucket="3_10"} 717
telemt_desync_frames_bucket_total{bucket="gt_10"} 820
telemt_pool_swap_total 154
telemt_me_writer_removed_unexpected_total 34207
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 33674
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 513
telemt_user_connections_total{user="hello"} 545905
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 16013691674 (14.91 GB)
telemt_user_octets_to_client{user="hello"} 265155203144 (246.95 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 167186.5 (46h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 324976
telemt_connections_bad_total 2289
telemt_handshake_timeouts_total 2378
telemt_upstream_connect_attempt_total 149163
telemt_upstream_connect_success_total 147930
telemt_upstream_connect_fail_total 1233
telemt_upstream_connect_attempts_per_request{bucket="1"} 149163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36029
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2420
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1233
telemt_me_keepalive_timeout_total 3943
telemt_me_reconnect_attempts_total 174265
telemt_me_reconnect_success_total 36301
telemt_me_reader_eof_total 41567
telemt_me_idle_close_by_peer_total 41567
telemt_me_route_drop_no_conn_total 104971
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 204745
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 42
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
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 40950
telemt_me_refill_failed_total 4305
telemt_me_writer_restored_same_endpoint_total 36284
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4649
telemt_user_connections_total{user="hello"} 307851
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 3189595851 (2.97 GB)
telemt_user_octets_to_client{user="hello"} 100364691499 (93.47 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 167150.2 (46h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 378250
telemt_connections_bad_total 2965
telemt_handshake_timeouts_total 34928
telemt_upstream_connect_attempt_total 44232
telemt_upstream_connect_success_total 44223
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 44232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23973
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3419
telemt_me_reconnect_attempts_total 37146
telemt_me_reconnect_success_total 35862
telemt_me_reader_eof_total 38561
telemt_me_idle_close_by_peer_total 38561
telemt_me_route_drop_no_conn_total 136212
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 327244
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
telemt_pool_swap_total 158
telemt_me_writer_removed_unexpected_total 36295
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 35841
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 433
telemt_user_connections_total{user="hello"} 327016
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 13350369872 (12.43 GB)
telemt_user_octets_to_client{user="hello"} 129799114448 (120.88 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 167125.7 (46h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 479336
telemt_connections_bad_total 15653
telemt_handshake_timeouts_total 4479
telemt_upstream_connect_attempt_total 74346
telemt_upstream_connect_success_total 63790
telemt_upstream_connect_fail_total 10556
telemt_upstream_connect_attempts_per_request{bucket="1"} 74346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25656
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 336
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10556
telemt_me_keepalive_timeout_total 5318
telemt_me_reconnect_attempts_total 142493
telemt_me_reconnect_success_total 36438
telemt_me_reader_eof_total 40908
telemt_me_idle_close_by_peer_total 40900
telemt_me_route_drop_no_conn_total 172590
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 407485
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1730
telemt_desync_full_logged_total 512
telemt_desync_suppressed_total 1218
telemt_desync_frames_bucket_total{bucket="1_2"} 408
telemt_desync_frames_bucket_total{bucket="3_10"} 655
telemt_desync_frames_bucket_total{bucket="gt_10"} 667
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 40168
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 36428
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3730
telemt_user_connections_total{user="hello"} 426326
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 9256100663 (8.62 GB)
telemt_user_octets_to_client{user="hello"} 169349632068 (157.72 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 117297.2 (32h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192028
telemt_connections_bad_total 28453
telemt_handshake_timeouts_total 1663
telemt_upstream_connect_attempt_total 41798
telemt_upstream_connect_success_total 41403
telemt_upstream_connect_fail_total 395
telemt_upstream_connect_attempts_per_request{bucket="1"} 41798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 395
telemt_me_keepalive_timeout_total 2425
telemt_me_reconnect_attempts_total 44092
telemt_me_reconnect_success_total 30667
telemt_me_reader_eof_total 32827
telemt_me_idle_close_by_peer_total 32827
telemt_me_route_drop_no_conn_total 56799
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 151799
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 623
telemt_desync_full_logged_total 147
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 31367
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 30649
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 700
telemt_user_connections_total{user="hello"} 156548
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 2340501645 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 71178268735 (66.29 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 167081.9 (46h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 953750
telemt_connections_bad_total 35989
telemt_handshake_timeouts_total 25894
telemt_upstream_connect_attempt_total 34693
telemt_upstream_connect_success_total 34506
telemt_upstream_connect_fail_total 187
telemt_upstream_connect_attempts_per_request{bucket="1"} 34693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18251
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 187
telemt_me_keepalive_timeout_total 4613
telemt_me_reconnect_attempts_total 30920
telemt_me_reconnect_success_total 26244
telemt_me_reader_eof_total 28170
telemt_me_idle_close_by_peer_total 28167
telemt_me_route_drop_no_conn_total 449717
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 883910
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 760
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 158
telemt_me_writer_removed_unexpected_total 26724
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 26237
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 480
telemt_user_connections_total{user="hello"} 856563
telemt_user_connections_current{user="hello"} 410
telemt_user_octets_from_client{user="hello"} 14834609344 (13.82 GB)
telemt_user_octets_to_client{user="hello"} 436737801424 (406.74 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 69
```