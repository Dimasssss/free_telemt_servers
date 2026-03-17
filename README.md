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

# Server Metrics 2026-03-17 08:36:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 49891.1 (13h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 363945
telemt_connections_bad_total 3592
telemt_handshake_timeouts_total 10941
telemt_upstream_connect_attempt_total 10545
telemt_upstream_connect_success_total 10401
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 10545
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4840
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5504
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 9227
telemt_me_reconnect_success_total 7761
telemt_me_reader_eof_total 8263
telemt_me_idle_close_by_peer_total 8263
telemt_me_route_drop_no_conn_total 113418
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 329404
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2554
telemt_desync_full_logged_total 720
telemt_desync_suppressed_total 1834
telemt_desync_frames_bucket_total{bucket="1_2"} 589
telemt_desync_frames_bucket_total{bucket="3_10"} 1211
telemt_desync_frames_bucket_total{bucket="gt_10"} 754
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7916
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 7740
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 329275
telemt_user_connections_current{user="hello"} 966
telemt_user_octets_from_client{user="hello"} 4661937834 (4.34 GB)
telemt_user_octets_to_client{user="hello"} 134403964170 (125.17 GB)
telemt_user_msgs_from_client{user="hello"} 275
telemt_user_msgs_to_client{user="hello"} 314
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 50142.7 (13h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 200131
telemt_connections_bad_total 2370
telemt_handshake_timeouts_total 12270
telemt_upstream_connect_attempt_total 13610
telemt_upstream_connect_success_total 13431
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 13610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7579
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_reconnect_attempts_total 13227
telemt_me_reconnect_success_total 10954
telemt_me_reader_eof_total 11583
telemt_me_idle_close_by_peer_total 11583
telemt_me_route_drop_no_conn_total 72908
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175490
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 464
telemt_desync_full_logged_total 167
telemt_desync_suppressed_total 297
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 200
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 11134
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 10938
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 175501
telemt_user_connections_current{user="hello"} 449
telemt_user_octets_from_client{user="hello"} 2117743636 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 69913363208 (65.11 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 49918.7 (13h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123328
telemt_connections_bad_total 7518
telemt_handshake_timeouts_total 6655
telemt_upstream_connect_attempt_total 13220
telemt_upstream_connect_success_total 13150
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 13220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7274
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 11594
telemt_me_reconnect_success_total 10632
telemt_me_reader_eof_total 11376
telemt_me_idle_close_by_peer_total 11376
telemt_me_route_drop_no_conn_total 38360
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100199
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 263
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 199
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 102
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10798
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 10621
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 100139
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 6594551636 (6.14 GB)
telemt_user_octets_to_client{user="hello"} 31713135228 (29.54 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 49978.0 (13h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266577
telemt_connections_bad_total 6175
telemt_handshake_timeouts_total 10528
telemt_upstream_connect_attempt_total 11440
telemt_upstream_connect_success_total 11340
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 11440
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5908
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 9857
telemt_me_reconnect_success_total 8787
telemt_me_reader_eof_total 9353
telemt_me_idle_close_by_peer_total 9353
telemt_me_route_drop_no_conn_total 71825
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 208281
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 433
telemt_desync_full_logged_total 157
telemt_desync_suppressed_total 276
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 182
telemt_desync_frames_bucket_total{bucket="gt_10"} 142
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8951
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8779
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 208271
telemt_user_connections_current{user="hello"} 601
telemt_user_octets_from_client{user="hello"} 2236146662 (2.08 GB)
telemt_user_octets_to_client{user="hello"} 90477913421 (84.26 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 49949.9 (13h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150464
telemt_connections_bad_total 40294
telemt_handshake_timeouts_total 2653
telemt_upstream_connect_attempt_total 15342
telemt_upstream_connect_success_total 15139
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 15342
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8181
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_reconnect_attempts_total 19635
telemt_me_reconnect_success_total 12528
telemt_me_reader_eof_total 13298
telemt_me_idle_close_by_peer_total 13298
telemt_me_route_drop_no_conn_total 39685
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102761
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 283
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 215
telemt_desync_frames_bucket_total{bucket="1_2"} 131
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 12902
telemt_me_refill_failed_total 220
telemt_me_writer_restored_same_endpoint_total 12520
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 374
telemt_user_connections_total{user="hello"} 102793
telemt_user_connections_current{user="hello"} 276
telemt_user_octets_from_client{user="hello"} 1676614711 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 48107036590 (44.80 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 50111.5 (13h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 364656
telemt_connections_bad_total 46205
telemt_handshake_timeouts_total 3598
telemt_upstream_connect_attempt_total 10290
telemt_upstream_connect_success_total 10234
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 10290
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5230
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 11621
telemt_me_reconnect_success_total 7745
telemt_me_reader_eof_total 8373
telemt_me_idle_close_by_peer_total 8373
telemt_me_route_drop_no_conn_total 254502
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 372187
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 468
telemt_desync_full_logged_total 189
telemt_desync_suppressed_total 279
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 170
telemt_desync_frames_bucket_total{bucket="gt_10"} 154
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7979
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 7731
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 294097
telemt_user_connections_current{user="hello"} 803
telemt_user_octets_from_client{user="hello"} 4120315700 (3.84 GB)
telemt_user_octets_to_client{user="hello"} 172904261296 (161.03 GB)
telemt_user_unique_ips_current{user="hello"} 278
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 38117.3 (10h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3277
telemt_connections_bad_total 207
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 18648
telemt_upstream_connect_success_total 18644
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 18648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 16753
telemt_me_reconnect_success_total 16648
telemt_me_reader_eof_total 18190
telemt_me_idle_close_by_peer_total 18190
telemt_me_route_drop_no_conn_total 630
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3011
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 16799
telemt_me_writer_restored_same_endpoint_total 16648
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 3011
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 719627108 (686.29 MB)
telemt_user_octets_to_client{user="hello"} 19935240364 (18.57 GB)
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 9
```