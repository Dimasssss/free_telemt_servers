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

# Server Metrics 2026-03-15 17:26:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 69119.4 (19h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 321357
telemt_connections_bad_total 3263
telemt_handshake_timeouts_total 9264
telemt_upstream_connect_attempt_total 16841
telemt_upstream_connect_success_total 16754
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 16841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9305
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 16702
telemt_me_reconnect_success_total 13307
telemt_me_reader_eof_total 14168
telemt_me_idle_close_by_peer_total 14168
telemt_me_route_drop_no_conn_total 459094
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 357245
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1837
telemt_desync_full_logged_total 728
telemt_desync_suppressed_total 1109
telemt_desync_frames_bucket_total{bucket="1_2"} 338
telemt_desync_frames_bucket_total{bucket="3_10"} 724
telemt_desync_frames_bucket_total{bucket="gt_10"} 775
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 13556
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 13273
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 249
telemt_user_connections_total{user="hello"} 296345
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 6097637628 (5.68 GB)
telemt_user_octets_to_client{user="hello"} 236754680824 (220.49 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 69126.1 (19h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126652
telemt_connections_bad_total 2827
telemt_handshake_timeouts_total 11685
telemt_upstream_connect_attempt_total 18879
telemt_upstream_connect_success_total 18879
telemt_upstream_connect_attempts_per_request{bucket="1"} 18879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10523
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 267
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 17754
telemt_me_reconnect_success_total 15391
telemt_me_reader_eof_total 16451
telemt_me_idle_close_by_peer_total 16450
telemt_me_route_drop_no_conn_total 53270
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108315
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 15660
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 15375
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 108298
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 2077284532 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 53783814068 (50.09 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 69118.7 (19h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132235
telemt_connections_bad_total 1695
telemt_handshake_timeouts_total 3170
telemt_upstream_connect_attempt_total 20392
telemt_upstream_connect_success_total 20384
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 20392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11521
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 24238
telemt_me_reconnect_success_total 16882
telemt_me_reader_eof_total 18117
telemt_me_idle_close_by_peer_total 18117
telemt_me_route_drop_no_conn_total 51773
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115909
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 59
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 17273
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 16874
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 391
telemt_user_connections_total{user="hello"} 115803
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 10650058480 (9.92 GB)
telemt_user_octets_to_client{user="hello"} 65903635608 (61.38 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 69118.2 (19h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179220
telemt_connections_bad_total 927
telemt_handshake_timeouts_total 1168
telemt_upstream_connect_attempt_total 16480
telemt_upstream_connect_success_total 16468
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 16480
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8499
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 13103
telemt_me_reconnect_success_total 13022
telemt_me_reader_eof_total 13856
telemt_me_idle_close_by_peer_total 13856
telemt_me_route_drop_no_conn_total 69257
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165251
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 577
telemt_desync_full_logged_total 208
telemt_desync_suppressed_total 369
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 265
telemt_desync_frames_bucket_total{bucket="gt_10"} 192
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 13181
telemt_me_writer_restored_same_endpoint_total 13011
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 165164
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 3078215556 (2.87 GB)
telemt_user_octets_to_client{user="hello"} 74154534812 (69.06 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 44189.8 (12h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109446
telemt_connections_bad_total 23426
telemt_handshake_timeouts_total 2430
telemt_upstream_connect_attempt_total 13398
telemt_upstream_connect_success_total 13321
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 13398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7148
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 105355
telemt_me_reconnect_success_total 10914
telemt_me_reader_eof_total 11449
telemt_me_idle_close_by_peer_total 11449
telemt_me_route_drop_no_conn_total 37346
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80691
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 194
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 147
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 76
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 10973
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 10810
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 80824
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 1376549265 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 31789136043 (29.61 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 69118.9 (19h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 459081
telemt_connections_bad_total 57575
telemt_handshake_timeouts_total 3777
telemt_upstream_connect_attempt_total 14957
telemt_upstream_connect_success_total 14868
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 14957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7617
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 12696
telemt_me_reconnect_success_total 11392
telemt_me_reader_eof_total 12104
telemt_me_idle_close_by_peer_total 12104
telemt_me_route_drop_no_conn_total 280460
telemt_me_route_drop_channel_closed_total 71
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 413578
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 317
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 11554
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 11365
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 380824
telemt_user_connections_current{user="hello"} 631
telemt_user_octets_from_client{user="hello"} 10142471064 (9.45 GB)
telemt_user_octets_to_client{user="hello"} 202229532496 (188.34 GB)
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 81
```