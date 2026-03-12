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

# Server Metrics 2026-03-12 21:02:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 48556.5 (13h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233540
telemt_connections_bad_total 2674
telemt_handshake_timeouts_total 5160
telemt_upstream_connect_attempt_total 12156
telemt_upstream_connect_success_total 12100
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 12156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6714
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1454
telemt_me_reconnect_attempts_total 13103
telemt_me_reconnect_success_total 9639
telemt_me_reader_eof_total 10237
telemt_me_idle_close_by_peer_total 10236
telemt_me_route_drop_no_conn_total 71812
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193420
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 665
telemt_desync_full_logged_total 247
telemt_desync_suppressed_total 418
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 251
telemt_desync_frames_bucket_total{bucket="gt_10"} 293
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 9858
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 9623
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 219
telemt_user_connections_total{user="hello"} 193187
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 3656332000 (3.41 GB)
telemt_user_octets_to_client{user="hello"} 93023533660 (86.63 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 48449.5 (13h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104467
telemt_connections_bad_total 545
telemt_handshake_timeouts_total 801
telemt_upstream_connect_attempt_total 29717
telemt_upstream_connect_success_total 29405
telemt_upstream_connect_fail_total 312
telemt_upstream_connect_attempts_per_request{bucket="1"} 29717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8886
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 493
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 312
telemt_me_keepalive_timeout_total 361
telemt_me_reconnect_attempts_total 49891
telemt_me_reconnect_success_total 10458
telemt_me_reader_eof_total 11893
telemt_me_idle_close_by_peer_total 11893
telemt_me_route_drop_no_conn_total 37831
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82820
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 11770
telemt_me_refill_failed_total 1231
telemt_me_writer_restored_same_endpoint_total 10443
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1312
telemt_user_connections_total{user="hello"} 99323
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 1089560140 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 29268587719 (27.26 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 48413.0 (13h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130163
telemt_connections_bad_total 1549
telemt_handshake_timeouts_total 2205
telemt_upstream_connect_attempt_total 13395
telemt_upstream_connect_success_total 13394
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 13395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7041
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 299
telemt_me_reconnect_attempts_total 12050
telemt_me_reconnect_success_total 10911
telemt_me_reader_eof_total 11612
telemt_me_idle_close_by_peer_total 11612
telemt_me_route_drop_no_conn_total 49353
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121381
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 47
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 11052
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 10891
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 121351
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 2532664120 (2.36 GB)
telemt_user_octets_to_client{user="hello"} 57351882524 (53.41 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 48388.7 (13h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190081
telemt_connections_bad_total 13175
telemt_handshake_timeouts_total 1283
telemt_upstream_connect_attempt_total 24423
telemt_upstream_connect_success_total 14765
telemt_upstream_connect_fail_total 9658
telemt_upstream_connect_attempts_per_request{bucket="1"} 24423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6566
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9658
telemt_me_keepalive_timeout_total 2454
telemt_me_reconnect_attempts_total 41695
telemt_me_reconnect_success_total 9454
telemt_me_reader_eof_total 10769
telemt_me_idle_close_by_peer_total 10762
telemt_me_route_drop_no_conn_total 65920
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 154529
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 491
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 349
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 182
telemt_desync_frames_bucket_total{bucket="gt_10"} 186
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 10618
telemt_me_refill_failed_total 1004
telemt_me_writer_restored_same_endpoint_total 9444
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1164
telemt_user_connections_total{user="hello"} 157284
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 2906591962 (2.71 GB)
telemt_user_octets_to_client{user="hello"} 61300136109 (57.09 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 48345.2 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 302707
telemt_connections_bad_total 4065
telemt_handshake_timeouts_total 2401
telemt_upstream_connect_attempt_total 10091
telemt_upstream_connect_success_total 10040
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 10091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5347
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 489
telemt_me_reconnect_attempts_total 11217
telemt_me_reconnect_success_total 7610
telemt_me_reader_eof_total 8121
telemt_me_idle_close_by_peer_total 8120
telemt_me_route_drop_no_conn_total 138904
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 298770
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 285
telemt_desync_full_logged_total 108
telemt_desync_suppressed_total 177
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7818
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 7603
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 287075
telemt_user_connections_current{user="hello"} 278
telemt_user_octets_from_client{user="hello"} 5201562164 (4.84 GB)
telemt_user_octets_to_client{user="hello"} 140008705832 (130.39 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 25
```