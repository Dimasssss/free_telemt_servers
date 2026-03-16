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

# Server Metrics 2026-03-16 14:53:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 4527.2 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53338
telemt_connections_bad_total 304
telemt_handshake_timeouts_total 1284
telemt_upstream_connect_attempt_total 820
telemt_upstream_connect_success_total 818
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 423
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 569
telemt_me_reconnect_success_total 562
telemt_me_reader_eof_total 551
telemt_me_idle_close_by_peer_total 551
telemt_me_route_drop_no_conn_total 15105
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49648
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 203
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 160
telemt_desync_frames_bucket_total{bucket="1_2"} 70
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 554
telemt_me_writer_restored_same_endpoint_total 560
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 49586
telemt_user_connections_current{user="hello"} 670
telemt_user_octets_from_client{user="hello"} 1148994308 (1.07 GB)
telemt_user_octets_to_client{user="hello"} 30435564592 (28.35 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 2091.3 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21418
telemt_connections_bad_total 281
telemt_handshake_timeouts_total 113
telemt_upstream_connect_attempt_total 20313
telemt_upstream_connect_success_total 20294
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 20311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1084
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2166
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20292
telemt_user_connections_current{user="hello"} 510
telemt_user_octets_from_client{user="hello"} 247016828 (235.57 MB)
telemt_user_octets_to_client{user="hello"} 4131060998 (3.85 GB)
telemt_user_msgs_from_client{user="hello"} 307473
telemt_user_msgs_to_client{user="hello"} 1205624
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 4640.0 (1h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21114
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 155
telemt_upstream_connect_attempt_total 2323
telemt_upstream_connect_success_total 2288
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 2323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 908
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_reconnect_attempts_total 32127
telemt_me_reconnect_success_total 1033
telemt_me_reader_eof_total 1085
telemt_me_idle_close_by_peer_total 1085
telemt_me_route_drop_no_conn_total 5650
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18929
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_me_writer_removed_unexpected_total 1108
telemt_me_refill_failed_total 971
telemt_me_writer_restored_same_endpoint_total 989
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 19883
telemt_user_connections_current{user="hello"} 293
telemt_user_octets_from_client{user="hello"} 220972170 (210.74 MB)
telemt_user_octets_to_client{user="hello"} 3312623586 (3.09 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 4776.2 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37959
telemt_connections_bad_total 26
telemt_handshake_timeouts_total 645
telemt_upstream_connect_attempt_total 1077
telemt_upstream_connect_success_total 1071
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 512
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 4353
telemt_me_reconnect_success_total 752
telemt_me_reader_eof_total 841
telemt_me_idle_close_by_peer_total 841
telemt_me_route_drop_no_conn_total 12203
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35777
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 208
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 155
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_me_writer_removed_unexpected_total 862
telemt_me_refill_failed_total 112
telemt_me_writer_restored_same_endpoint_total 748
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 35757
telemt_user_connections_current{user="hello"} 449
telemt_user_octets_from_client{user="hello"} 733252872 (699.28 MB)
telemt_user_octets_to_client{user="hello"} 8631415444 (8.04 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 2236.6 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12179
telemt_connections_bad_total 4112
telemt_handshake_timeouts_total 51
telemt_upstream_connect_attempt_total 546
telemt_upstream_connect_success_total 538
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 386
telemt_me_reconnect_success_total 380
telemt_me_reader_eof_total 362
telemt_me_idle_close_by_peer_total 362
telemt_me_route_drop_no_conn_total 2418
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7580
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 378
telemt_me_writer_restored_same_endpoint_total 380
telemt_me_async_recovery_trigger_total 22
telemt_user_connections_total{user="hello"} 7566
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 231859164 (221.12 MB)
telemt_user_octets_to_client{user="hello"} 1132302296 (1.05 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 4344.1 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54690
telemt_connections_bad_total 1076
telemt_handshake_timeouts_total 1177
telemt_upstream_connect_attempt_total 914
telemt_upstream_connect_success_total 914
telemt_upstream_connect_attempts_per_request{bucket="1"} 914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 450
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 3032
telemt_me_reconnect_success_total 660
telemt_me_reader_eof_total 710
telemt_me_idle_close_by_peer_total 710
telemt_me_route_drop_no_conn_total 22444
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50999
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_me_writer_removed_unexpected_total 732
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 656
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 50868
telemt_user_connections_current{user="hello"} 754
telemt_user_octets_from_client{user="hello"} 1194464588 (1.11 GB)
telemt_user_octets_to_client{user="hello"} 13861270296 (12.91 GB)
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 100
```