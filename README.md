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

# Server Metrics 2026-03-12 19:04:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 41420.8 (11h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209040
telemt_connections_bad_total 2610
telemt_handshake_timeouts_total 4971
telemt_upstream_connect_attempt_total 10504
telemt_upstream_connect_success_total 10459
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 10504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5798
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 1425
telemt_me_reconnect_attempts_total 11805
telemt_me_reconnect_success_total 8347
telemt_me_reader_eof_total 8846
telemt_me_idle_close_by_peer_total 8845
telemt_me_route_drop_no_conn_total 62747
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175292
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
telemt_me_writer_removed_unexpected_total 8555
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 8331
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 175251
telemt_user_connections_current{user="hello"} 278
telemt_user_octets_from_client{user="hello"} 3087362676 (2.88 GB)
telemt_user_octets_to_client{user="hello"} 76657726672 (71.39 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 41313.9 (11h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92414
telemt_connections_bad_total 490
telemt_handshake_timeouts_total 716
telemt_upstream_connect_attempt_total 22859
telemt_upstream_connect_success_total 22590
telemt_upstream_connect_fail_total 269
telemt_upstream_connect_attempts_per_request{bucket="1"} 22859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7557
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 384
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 269
telemt_me_keepalive_timeout_total 329
telemt_me_reconnect_attempts_total 44432
telemt_me_reconnect_success_total 9128
telemt_me_reader_eof_total 10403
telemt_me_idle_close_by_peer_total 10403
telemt_me_route_drop_no_conn_total 35492
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
telemt_me_writer_removed_unexpected_total 10303
telemt_me_refill_failed_total 1102
telemt_me_writer_restored_same_endpoint_total 9113
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1175
telemt_user_connections_total{user="hello"} 87925
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 963694047 (919.05 MB)
telemt_user_octets_to_client{user="hello"} 25897686280 (24.12 GB)
telemt_user_msgs_from_client{user="hello"} 181110
telemt_user_msgs_to_client{user="hello"} 1520551
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 41277.3 (11h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119008
telemt_connections_bad_total 1516
telemt_handshake_timeouts_total 2145
telemt_upstream_connect_attempt_total 11543
telemt_upstream_connect_success_total 11543
telemt_upstream_connect_attempts_per_request{bucket="1"} 11543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5983
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 266
telemt_me_reconnect_attempts_total 10545
telemt_me_reconnect_success_total 9412
telemt_me_reader_eof_total 9987
telemt_me_idle_close_by_peer_total 9987
telemt_me_route_drop_no_conn_total 44761
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 110579
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 41
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 9536
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 9392
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 110552
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 2457076572 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 55555265300 (51.74 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 41253.0 (11h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171479
telemt_connections_bad_total 13151
telemt_handshake_timeouts_total 1246
telemt_upstream_connect_attempt_total 22163
telemt_upstream_connect_success_total 12560
telemt_upstream_connect_fail_total 9603
telemt_upstream_connect_attempts_per_request{bucket="1"} 22163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5360
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9603
telemt_me_keepalive_timeout_total 2419
telemt_me_reconnect_attempts_total 38781
telemt_me_reconnect_success_total 7600
telemt_me_reader_eof_total 8801
telemt_me_idle_close_by_peer_total 8794
telemt_me_route_drop_no_conn_total 58457
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137097
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 468
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 333
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 174
telemt_desync_frames_bucket_total{bucket="gt_10"} 172
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 8709
telemt_me_refill_failed_total 971
telemt_me_writer_restored_same_endpoint_total 7590
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1109
telemt_user_connections_total{user="hello"} 139854
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 2567270130 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 55914059197 (52.07 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 41209.8 (11h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 262510
telemt_connections_bad_total 2130
telemt_handshake_timeouts_total 2162
telemt_upstream_connect_attempt_total 8726
telemt_upstream_connect_success_total 8681
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 8726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4644
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 471
telemt_me_reconnect_attempts_total 10204
telemt_me_reconnect_success_total 6599
telemt_me_reader_eof_total 7031
telemt_me_idle_close_by_peer_total 7030
telemt_me_route_drop_no_conn_total 122313
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 261094
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
telemt_me_writer_removed_unexpected_total 6794
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 6592
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 249933
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 4330380556 (4.03 GB)
telemt_user_octets_to_client{user="hello"} 120376904920 (112.11 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 56
```