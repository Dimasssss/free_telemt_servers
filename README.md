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

# Server Metrics 2026-03-17 03:00:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 29725.7 (8h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155798
telemt_connections_bad_total 2376
telemt_handshake_timeouts_total 5451
telemt_upstream_connect_attempt_total 6368
telemt_upstream_connect_success_total 6330
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 6368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3477
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4872
telemt_me_reconnect_success_total 4856
telemt_me_reader_eof_total 5163
telemt_me_idle_close_by_peer_total 5163
telemt_me_route_drop_no_conn_total 48669
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 141107
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 797
telemt_desync_full_logged_total 277
telemt_desync_suppressed_total 520
telemt_desync_frames_bucket_total{bucket="1_2"} 184
telemt_desync_frames_bucket_total{bucket="3_10"} 404
telemt_desync_frames_bucket_total{bucket="gt_10"} 209
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 4898
telemt_me_writer_restored_same_endpoint_total 4835
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 141041
telemt_user_connections_current{user="hello"} 376
telemt_user_octets_from_client{user="hello"} 1906910016 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 63044591172 (58.71 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 29976.8 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87279
telemt_connections_bad_total 1358
telemt_handshake_timeouts_total 2960
telemt_upstream_connect_attempt_total 8265
telemt_upstream_connect_success_total 8155
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 8265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4707
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_reconnect_attempts_total 7816
telemt_me_reconnect_success_total 6649
telemt_me_reader_eof_total 7034
telemt_me_idle_close_by_peer_total 7034
telemt_me_route_drop_no_conn_total 37011
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79359
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 186
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 125
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6750
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 6633
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 79303
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 1150500224 (1.07 GB)
telemt_user_octets_to_client{user="hello"} 37080424972 (34.53 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 29753.0 (8h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56700
telemt_connections_bad_total 785
telemt_handshake_timeouts_total 1929
telemt_upstream_connect_attempt_total 8002
telemt_upstream_connect_success_total 7956
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 8002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3503
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4393
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 6490
telemt_me_reconnect_success_total 6453
telemt_me_reader_eof_total 6894
telemt_me_idle_close_by_peer_total 6894
telemt_me_route_drop_no_conn_total 17912
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47804
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 29
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 6536
telemt_me_writer_restored_same_endpoint_total 6442
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 47788
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 5568084112 (5.19 GB)
telemt_user_octets_to_client{user="hello"} 17675415936 (16.46 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 29812.3 (8h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88424
telemt_connections_bad_total 3377
telemt_handshake_timeouts_total 1291
telemt_upstream_connect_attempt_total 6947
telemt_upstream_connect_success_total 6885
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 6947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3618
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_reconnect_attempts_total 5398
telemt_me_reconnect_success_total 5360
telemt_me_reader_eof_total 5691
telemt_me_idle_close_by_peer_total 5691
telemt_me_route_drop_no_conn_total 30603
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81286
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 152
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 106
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 5436
telemt_me_writer_restored_same_endpoint_total 5353
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 81270
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 935308304 (891.98 MB)
telemt_user_octets_to_client{user="hello"} 37706540748 (35.12 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 29784.1 (8h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67515
telemt_connections_bad_total 16017
telemt_handshake_timeouts_total 1011
telemt_upstream_connect_attempt_total 8780
telemt_upstream_connect_success_total 8668
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 8779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4631
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_reconnect_attempts_total 9412
telemt_me_reconnect_success_total 7163
telemt_me_reader_eof_total 7550
telemt_me_idle_close_by_peer_total 7550
telemt_me_route_drop_no_conn_total 19301
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48561
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 7341
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 7155
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 48555
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 562916328 (536.84 MB)
telemt_user_octets_to_client{user="hello"} 15182419804 (14.14 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 29945.2 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169284
telemt_connections_bad_total 12252
telemt_handshake_timeouts_total 1096
telemt_upstream_connect_attempt_total 6224
telemt_upstream_connect_success_total 6189
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 6224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3251
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_reconnect_attempts_total 4698
telemt_me_reconnect_success_total 4681
telemt_me_reader_eof_total 5024
telemt_me_idle_close_by_peer_total 5024
telemt_me_route_drop_no_conn_total 179102
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 228135
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 142
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 58
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 4749
telemt_me_writer_restored_same_endpoint_total 4671
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 150386
telemt_user_connections_current{user="hello"} 341
telemt_user_octets_from_client{user="hello"} 2399803932 (2.23 GB)
telemt_user_octets_to_client{user="hello"} 120545700564 (112.27 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 17951.6 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156
telemt_connections_bad_total 118
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 9023
telemt_upstream_connect_success_total 9023
telemt_upstream_connect_attempts_per_request{bucket="1"} 9023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3777
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 8131
telemt_me_reconnect_success_total 8087
telemt_me_reader_eof_total 8855
telemt_me_idle_close_by_peer_total 8855
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 8168
telemt_me_writer_restored_same_endpoint_total 8087
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```