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

# Server Metrics 2026-03-15 07:24:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 32998.3 (9h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102369
telemt_connections_bad_total 708
telemt_handshake_timeouts_total 2355
telemt_upstream_connect_attempt_total 7942
telemt_upstream_connect_success_total 7895
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 7942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4300
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6276
telemt_me_reconnect_success_total 6253
telemt_me_reader_eof_total 6697
telemt_me_idle_close_by_peer_total 6697
telemt_me_route_drop_no_conn_total 133608
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113011
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 845
telemt_desync_full_logged_total 364
telemt_desync_suppressed_total 481
telemt_desync_frames_bucket_total{bucket="1_2"} 145
telemt_desync_frames_bucket_total{bucket="3_10"} 350
telemt_desync_frames_bucket_total{bucket="gt_10"} 350
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 6306
telemt_me_writer_restored_same_endpoint_total 6222
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 95346
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 1332977664 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 69265479096 (64.51 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 33005.8 (9h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33437
telemt_connections_bad_total 233
telemt_handshake_timeouts_total 494
telemt_upstream_connect_attempt_total 8816
telemt_upstream_connect_success_total 8816
telemt_upstream_connect_attempts_per_request{bucket="1"} 8816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3872
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4934
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7193
telemt_me_reconnect_success_total 7163
telemt_me_reader_eof_total 7700
telemt_me_idle_close_by_peer_total 7700
telemt_me_route_drop_no_conn_total 17291
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31403
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 7229
telemt_me_writer_restored_same_endpoint_total 7147
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 31406
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 784379440 (748.04 MB)
telemt_user_octets_to_client{user="hello"} 12135102304 (11.30 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 32998.6 (9h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42289
telemt_connections_bad_total 459
telemt_handshake_timeouts_total 1807
telemt_upstream_connect_attempt_total 8744
telemt_upstream_connect_success_total 8743
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4897
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 7123
telemt_me_reconnect_success_total 7092
telemt_me_reader_eof_total 7671
telemt_me_idle_close_by_peer_total 7671
telemt_me_route_drop_no_conn_total 14597
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38142
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 7154
telemt_me_writer_restored_same_endpoint_total 7088
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 38080
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 8842572052 (8.24 GB)
telemt_user_octets_to_client{user="hello"} 20349843448 (18.95 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 32998.2 (9h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49010
telemt_connections_bad_total 135
telemt_handshake_timeouts_total 349
telemt_upstream_connect_attempt_total 7705
telemt_upstream_connect_success_total 7704
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7705
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4073
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 6089
telemt_me_reconnect_success_total 6065
telemt_me_reader_eof_total 6502
telemt_me_idle_close_by_peer_total 6502
telemt_me_route_drop_no_conn_total 21264
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44153
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 85
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 29
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 6128
telemt_me_writer_restored_same_endpoint_total 6054
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 44073
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 812023476 (774.41 MB)
telemt_user_octets_to_client{user="hello"} 27023265792 (25.17 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 8069.6 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11620
telemt_connections_bad_total 1575
telemt_handshake_timeouts_total 156
telemt_upstream_connect_attempt_total 3233
telemt_upstream_connect_success_total 3196
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 3233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1793
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 97021
telemt_me_reconnect_success_total 2626
telemt_me_reader_eof_total 2642
telemt_me_idle_close_by_peer_total 2642
telemt_me_route_drop_no_conn_total 3295
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9520
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2569
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 2522
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 9665
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 74310649 (70.87 MB)
telemt_user_octets_to_client{user="hello"} 8341579223 (7.77 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 32997.4 (9h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136493
telemt_connections_bad_total 19357
telemt_handshake_timeouts_total 549
telemt_upstream_connect_attempt_total 7157
telemt_upstream_connect_success_total 7115
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 7157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3530
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_reconnect_attempts_total 5493
telemt_me_reconnect_success_total 5467
telemt_me_reader_eof_total 5829
telemt_me_idle_close_by_peer_total 5829
telemt_me_route_drop_no_conn_total 64017
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113073
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 28
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 15
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5495
telemt_me_writer_restored_same_endpoint_total 5440
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 111607
telemt_user_connections_current{user="hello"} 376
telemt_user_octets_from_client{user="hello"} 2810896600 (2.62 GB)
telemt_user_octets_to_client{user="hello"} 58691491632 (54.66 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 57
```