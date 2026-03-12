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

# Server Metrics 2026-03-12 18:36:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 39799.4 (11h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202884
telemt_connections_bad_total 2418
telemt_handshake_timeouts_total 4959
telemt_upstream_connect_attempt_total 10163
telemt_upstream_connect_success_total 10119
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 10163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4491
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5601
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 11509
telemt_me_reconnect_success_total 8052
telemt_me_reader_eof_total 8534
telemt_me_idle_close_by_peer_total 8533
telemt_me_route_drop_no_conn_total 60586
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170843
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
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 8255
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 8036
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 203
telemt_user_connections_total{user="hello"} 170802
telemt_user_connections_current{user="hello"} 283
telemt_user_octets_from_client{user="hello"} 3016898120 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 73649399492 (68.59 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 39692.0 (11h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88520
telemt_connections_bad_total 472
telemt_handshake_timeouts_total 696
telemt_upstream_connect_attempt_total 19386
telemt_upstream_connect_success_total 19130
telemt_upstream_connect_fail_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 19385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7252
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 319
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 255
telemt_me_keepalive_timeout_total 328
telemt_me_reconnect_attempts_total 41652
telemt_me_reconnect_success_total 9100
telemt_me_reader_eof_total 10289
telemt_me_idle_close_by_peer_total 10289
telemt_me_route_drop_no_conn_total 35322
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76204
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 10
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
telemt_me_writer_removed_unexpected_total 10189
telemt_me_refill_failed_total 1016
telemt_me_writer_restored_same_endpoint_total 9085
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1089
telemt_user_connections_total{user="hello"} 84193
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 897341117 (855.77 MB)
telemt_user_octets_to_client{user="hello"} 23770316740 (22.14 GB)
telemt_user_msgs_from_client{user="hello"} 124892
telemt_user_msgs_to_client{user="hello"} 924666
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 39655.3 (11h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115154
telemt_connections_bad_total 1513
telemt_handshake_timeouts_total 2122
telemt_upstream_connect_attempt_total 11154
telemt_upstream_connect_success_total 11154
telemt_upstream_connect_attempts_per_request{bucket="1"} 11154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5768
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 261
telemt_me_reconnect_attempts_total 10219
telemt_me_reconnect_success_total 9087
telemt_me_reader_eof_total 9621
telemt_me_idle_close_by_peer_total 9621
telemt_me_route_drop_no_conn_total 43235
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106848
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
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 9209
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 9067
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 106820
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 2427705984 (2.26 GB)
telemt_user_octets_to_client{user="hello"} 54645314252 (50.89 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 39630.9 (11h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166443
telemt_connections_bad_total 13108
telemt_handshake_timeouts_total 1188
telemt_upstream_connect_attempt_total 21288
telemt_upstream_connect_success_total 11697
telemt_upstream_connect_fail_total 9591
telemt_upstream_connect_attempts_per_request{bucket="1"} 21288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5055
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9591
telemt_me_keepalive_timeout_total 2411
telemt_me_reconnect_attempts_total 37838
telemt_me_reconnect_success_total 7040
telemt_me_reader_eof_total 8194
telemt_me_idle_close_by_peer_total 8187
telemt_me_route_drop_no_conn_total 56700
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132496
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 320
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 168
telemt_desync_frames_bucket_total{bucket="gt_10"} 158
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 8129
telemt_me_refill_failed_total 959
telemt_me_writer_restored_same_endpoint_total 7030
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1089
telemt_user_connections_total{user="hello"} 135034
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 2456910393 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 54539054581 (50.79 GB)
telemt_user_msgs_from_client{user="hello"} 57644
telemt_user_msgs_to_client{user="hello"} 107476
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 39588.0 (10h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 252367
telemt_connections_bad_total 2019
telemt_handshake_timeouts_total 2130
telemt_upstream_connect_attempt_total 8389
telemt_upstream_connect_success_total 8346
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 8389
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 468
telemt_me_reconnect_attempts_total 9955
telemt_me_reconnect_success_total 6351
telemt_me_reader_eof_total 6765
telemt_me_idle_close_by_peer_total 6764
telemt_me_route_drop_no_conn_total 116065
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 250209
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
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 6545
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 6344
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 240134
telemt_user_connections_current{user="hello"} 372
telemt_user_octets_from_client{user="hello"} 4209054592 (3.92 GB)
telemt_user_octets_to_client{user="hello"} 109893075512 (102.35 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 53
```