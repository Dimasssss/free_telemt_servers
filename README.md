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

# Server Metrics 2026-03-15 10:33:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 44312.6 (12h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184126
telemt_connections_bad_total 1328
telemt_handshake_timeouts_total 4203
telemt_upstream_connect_attempt_total 11109
telemt_upstream_connect_success_total 11050
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 11109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6103
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 11191
telemt_me_reconnect_success_total 8818
telemt_me_reader_eof_total 9434
telemt_me_idle_close_by_peer_total 9434
telemt_me_route_drop_no_conn_total 412229
telemt_me_route_drop_channel_closed_total 60
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 232665
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1376
telemt_desync_full_logged_total 548
telemt_desync_suppressed_total 828
telemt_desync_frames_bucket_total{bucket="1_2"} 223
telemt_desync_frames_bucket_total{bucket="3_10"} 548
telemt_desync_frames_bucket_total{bucket="gt_10"} 605
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 8975
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 8787
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 171925
telemt_user_connections_current{user="hello"} 402
telemt_user_octets_from_client{user="hello"} 2708260156 (2.52 GB)
telemt_user_octets_to_client{user="hello"} 178110563780 (165.88 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 44319.4 (12h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59341
telemt_connections_bad_total 2309
telemt_handshake_timeouts_total 3053
telemt_upstream_connect_attempt_total 11909
telemt_upstream_connect_success_total 11909
telemt_upstream_connect_attempts_per_request{bucket="1"} 11909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6711
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 11979
telemt_me_reconnect_success_total 9657
telemt_me_reader_eof_total 10374
telemt_me_idle_close_by_peer_total 10374
telemt_me_route_drop_no_conn_total 28132
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52082
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 9835
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 9641
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 52080
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 1021874452 (974.54 MB)
telemt_user_octets_to_client{user="hello"} 22548643464 (21.00 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 44312.2 (12h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66960
telemt_connections_bad_total 645
telemt_handshake_timeouts_total 2436
telemt_upstream_connect_attempt_total 12328
telemt_upstream_connect_success_total 12327
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7054
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 11149
telemt_me_reconnect_success_total 10078
telemt_me_reader_eof_total 10838
telemt_me_idle_close_by_peer_total 10838
telemt_me_route_drop_no_conn_total 25144
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61227
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 30
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 10202
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 10074
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 61151
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 9296525528 (8.66 GB)
telemt_user_octets_to_client{user="hello"} 37675881788 (35.09 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 44311.5 (12h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86970
telemt_connections_bad_total 207
telemt_handshake_timeouts_total 591
telemt_upstream_connect_attempt_total 10489
telemt_upstream_connect_success_total 10488
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5450
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 8302
telemt_me_reconnect_success_total 8262
telemt_me_reader_eof_total 8818
telemt_me_idle_close_by_peer_total 8818
telemt_me_route_drop_no_conn_total 36170
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79254
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 163
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 113
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 8347
telemt_me_writer_restored_same_endpoint_total 8251
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 79184
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 1586542212 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 49377728492 (45.99 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 19383.0 (5h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32767
telemt_connections_bad_total 3623
telemt_handshake_timeouts_total 495
telemt_upstream_connect_attempt_total 6498
telemt_upstream_connect_success_total 6447
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 6498
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2895
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3532
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 99700
telemt_me_reconnect_success_total 5291
telemt_me_reader_eof_total 5476
telemt_me_idle_close_by_peer_total 5476
telemt_me_route_drop_no_conn_total 10999
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27847
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 40
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 5262
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 5187
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 27987
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 432819633 (412.77 MB)
telemt_user_octets_to_client{user="hello"} 12765910067 (11.89 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 44311.2 (12h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236510
telemt_connections_bad_total 44284
telemt_handshake_timeouts_total 1479
telemt_upstream_connect_attempt_total 9458
telemt_upstream_connect_success_total 9401
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 9458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 7210
telemt_me_reconnect_success_total 7167
telemt_me_reader_eof_total 7644
telemt_me_idle_close_by_peer_total 7644
telemt_me_route_drop_no_conn_total 103570
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 184467
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 76
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 38
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 7221
telemt_me_writer_restored_same_endpoint_total 7140
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 182837
telemt_user_connections_current{user="hello"} 541
telemt_user_octets_from_client{user="hello"} 4451477320 (4.15 GB)
telemt_user_octets_to_client{user="hello"} 93506347588 (87.08 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 76
```