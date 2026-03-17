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

# Server Metrics 2026-03-17 06:09:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 41035.6 (11h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 237050
telemt_connections_bad_total 3342
telemt_handshake_timeouts_total 7758
telemt_upstream_connect_attempt_total 8605
telemt_upstream_connect_success_total 8559
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 8605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6542
telemt_me_reconnect_success_total 6518
telemt_me_reader_eof_total 6937
telemt_me_idle_close_by_peer_total 6937
telemt_me_route_drop_no_conn_total 73548
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 214244
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1491
telemt_desync_full_logged_total 483
telemt_desync_suppressed_total 1008
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 768
telemt_desync_frames_bucket_total{bucket="gt_10"} 375
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 6582
telemt_me_writer_restored_same_endpoint_total 6497
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 214042
telemt_user_connections_current{user="hello"} 640
telemt_user_octets_from_client{user="hello"} 2920979484 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 93898596436 (87.45 GB)
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 41286.9 (11h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135310
telemt_connections_bad_total 2207
telemt_handshake_timeouts_total 10477
telemt_upstream_connect_attempt_total 11348
telemt_upstream_connect_success_total 11201
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 11347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6444
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_reconnect_attempts_total 10346
telemt_me_reconnect_success_total 9169
telemt_me_reader_eof_total 9701
telemt_me_idle_close_by_peer_total 9701
telemt_me_route_drop_no_conn_total 51210
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117707
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 314
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 200
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 152
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 9290
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 9153
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 117717
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 1459089112 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 50305420052 (46.85 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 41063.3 (11h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81023
telemt_connections_bad_total 1109
telemt_handshake_timeouts_total 2643
telemt_upstream_connect_attempt_total 11056
telemt_upstream_connect_success_total 10998
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 11056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6073
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 8986
telemt_me_reconnect_success_total 8937
telemt_me_reader_eof_total 9564
telemt_me_idle_close_by_peer_total 9564
telemt_me_route_drop_no_conn_total 27301
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69752
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 49
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 27
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 9045
telemt_me_writer_restored_same_endpoint_total 8926
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 69735
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 6065899328 (5.65 GB)
telemt_user_octets_to_client{user="hello"} 22675050756 (21.12 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 41122.2 (11h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141396
telemt_connections_bad_total 3785
telemt_handshake_timeouts_total 5933
telemt_upstream_connect_attempt_total 9332
telemt_upstream_connect_success_total 9252
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 9332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4877
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_reconnect_attempts_total 7209
telemt_me_reconnect_success_total 7154
telemt_me_reader_eof_total 7616
telemt_me_idle_close_by_peer_total 7616
telemt_me_route_drop_no_conn_total 47235
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 127536
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 236
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 164
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7258
telemt_me_writer_restored_same_endpoint_total 7147
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 127553
telemt_user_connections_current{user="hello"} 385
telemt_user_octets_from_client{user="hello"} 1380653618 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 61910000697 (57.66 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 41094.1 (11h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107404
telemt_connections_bad_total 31227
telemt_handshake_timeouts_total 2055
telemt_upstream_connect_attempt_total 12263
telemt_upstream_connect_success_total 12100
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 12263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6486
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 180
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_reconnect_attempts_total 12205
telemt_me_reconnect_success_total 9939
telemt_me_reader_eof_total 10494
telemt_me_idle_close_by_peer_total 10494
telemt_me_route_drop_no_conn_total 27676
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71225
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 39
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 10140
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 9931
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 71322
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 766111295 (730.62 MB)
telemt_user_octets_to_client{user="hello"} 30732335510 (28.62 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 41255.3 (11h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 255408
telemt_connections_bad_total 31429
telemt_handshake_timeouts_total 2113
telemt_upstream_connect_attempt_total 8455
telemt_upstream_connect_success_total 8410
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 8455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4382
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 6399
telemt_me_reconnect_success_total 6370
telemt_me_reader_eof_total 6824
telemt_me_idle_close_by_peer_total 6824
telemt_me_route_drop_no_conn_total 217085
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 290285
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 244
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 6463
telemt_me_writer_restored_same_endpoint_total 6360
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 212227
telemt_user_connections_current{user="hello"} 647
telemt_user_octets_from_client{user="hello"} 3196605292 (2.98 GB)
telemt_user_octets_to_client{user="hello"} 150828293360 (140.47 GB)
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 29261.7 (8h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 759
telemt_connections_bad_total 191
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 14424
telemt_upstream_connect_success_total 14424
telemt_upstream_connect_attempts_per_request{bucket="1"} 14424
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 12968
telemt_me_reconnect_success_total 12895
telemt_me_reader_eof_total 14161
telemt_me_idle_close_by_peer_total 14161
telemt_me_route_drop_no_conn_total 81
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 560
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 13011
telemt_me_writer_restored_same_endpoint_total 12895
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 560
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 186864040 (178.21 MB)
telemt_user_octets_to_client{user="hello"} 8454986080 (7.87 GB)
telemt_user_unique_ips_current{user="hello"} 5
```