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

# Server Metrics 2026-03-12 18:58:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 41096.4 (11h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207814
telemt_connections_bad_total 2610
telemt_handshake_timeouts_total 4968
telemt_upstream_connect_attempt_total 10460
telemt_upstream_connect_success_total 10415
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 10460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5762
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 1425
telemt_me_reconnect_attempts_total 11762
telemt_me_reconnect_success_total 8304
telemt_me_reader_eof_total 8803
telemt_me_idle_close_by_peer_total 8802
telemt_me_route_drop_no_conn_total 62330
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174348
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 636
telemt_desync_full_logged_total 240
telemt_desync_suppressed_total 396
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 242
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 8512
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 8288
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 174307
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 3073338644 (2.86 GB)
telemt_user_octets_to_client{user="hello"} 76230973708 (71.00 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 40989.5 (11h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91711
telemt_connections_bad_total 488
telemt_handshake_timeouts_total 711
telemt_upstream_connect_attempt_total 22178
telemt_upstream_connect_success_total 21910
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 22178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14042
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7504
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_keepalive_timeout_total 329
telemt_me_reconnect_attempts_total 44428
telemt_me_reconnect_success_total 9124
telemt_me_reader_eof_total 10399
telemt_me_idle_close_by_peer_total 10399
telemt_me_route_drop_no_conn_total 35471
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76561
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 11
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 10299
telemt_me_refill_failed_total 1102
telemt_me_writer_restored_same_endpoint_total 9109
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1175
telemt_user_connections_total{user="hello"} 87249
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 960593879 (916.09 MB)
telemt_user_octets_to_client{user="hello"} 25698196613 (23.93 GB)
telemt_user_msgs_from_client{user="hello"} 172867
telemt_user_msgs_to_client{user="hello"} 1464988
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 40953.1 (11h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118147
telemt_connections_bad_total 1515
telemt_handshake_timeouts_total 2139
telemt_upstream_connect_attempt_total 11501
telemt_upstream_connect_success_total 11501
telemt_upstream_connect_attempts_per_request{bucket="1"} 11501
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5957
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 266
telemt_me_reconnect_attempts_total 10503
telemt_me_reconnect_success_total 9370
telemt_me_reader_eof_total 9944
telemt_me_idle_close_by_peer_total 9944
telemt_me_route_drop_no_conn_total 44420
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109763
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 9493
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 9350
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 109735
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 2448170664 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 55125312980 (51.34 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 40928.6 (11h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170460
telemt_connections_bad_total 13133
telemt_handshake_timeouts_total 1242
telemt_upstream_connect_attempt_total 22119
telemt_upstream_connect_success_total 12516
telemt_upstream_connect_fail_total 9603
telemt_upstream_connect_attempts_per_request{bucket="1"} 22119
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5337
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9603
telemt_me_keepalive_timeout_total 2418
telemt_me_reconnect_attempts_total 38737
telemt_me_reconnect_success_total 7556
telemt_me_reader_eof_total 8757
telemt_me_idle_close_by_peer_total 8750
telemt_me_route_drop_no_conn_total 58021
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 136121
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 466
telemt_desync_full_logged_total 134
telemt_desync_suppressed_total 332
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 174
telemt_desync_frames_bucket_total{bucket="gt_10"} 170
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 8665
telemt_me_refill_failed_total 971
telemt_me_writer_restored_same_endpoint_total 7546
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1109
telemt_user_connections_total{user="hello"} 138878
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 2545848222 (2.37 GB)
telemt_user_octets_to_client{user="hello"} 55705442869 (51.88 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 40885.6 (11h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 260670
telemt_connections_bad_total 2130
telemt_handshake_timeouts_total 2153
telemt_upstream_connect_attempt_total 8682
telemt_upstream_connect_success_total 8637
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 8682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4620
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 470
telemt_me_reconnect_attempts_total 10160
telemt_me_reconnect_success_total 6556
telemt_me_reader_eof_total 6987
telemt_me_idle_close_by_peer_total 6986
telemt_me_route_drop_no_conn_total 121208
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 259297
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 255
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 6750
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 6549
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 248140
telemt_user_connections_current{user="hello"} 421
telemt_user_octets_from_client{user="hello"} 4314060148 (4.02 GB)
telemt_user_octets_to_client{user="hello"} 117897901904 (109.80 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 46
```