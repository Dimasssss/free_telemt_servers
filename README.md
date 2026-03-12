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

# Server Metrics 2026-03-12 19:31:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 43042.6 (11h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215287
telemt_connections_bad_total 2617
telemt_handshake_timeouts_total 4991
telemt_upstream_connect_attempt_total 10885
telemt_upstream_connect_success_total 10837
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 10885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6006
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 1431
telemt_me_reconnect_attempts_total 12098
telemt_me_reconnect_success_total 8639
telemt_me_reader_eof_total 9160
telemt_me_idle_close_by_peer_total 9159
telemt_me_route_drop_no_conn_total 64783
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180081
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 642
telemt_desync_full_logged_total 241
telemt_desync_suppressed_total 401
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 244
telemt_desync_frames_bucket_total{bucket="gt_10"} 278
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 8849
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 8623
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 180039
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 3251468540 (3.03 GB)
telemt_user_octets_to_client{user="hello"} 81429396852 (75.84 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 42935.2 (11h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96022
telemt_connections_bad_total 505
telemt_handshake_timeouts_total 769
telemt_upstream_connect_attempt_total 25866
telemt_upstream_connect_success_total 25584
telemt_upstream_connect_fail_total 282
telemt_upstream_connect_attempts_per_request{bucket="1"} 25866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7805
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 451
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 282
telemt_me_keepalive_timeout_total 331
telemt_me_reconnect_attempts_total 47202
telemt_me_reconnect_success_total 9146
telemt_me_reader_eof_total 10507
telemt_me_idle_close_by_peer_total 10507
telemt_me_route_drop_no_conn_total 35607
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77007
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
telemt_me_writer_removed_unexpected_total 10407
telemt_me_refill_failed_total 1188
telemt_me_writer_restored_same_endpoint_total 9131
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1261
telemt_user_connections_total{user="hello"} 91261
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 1006659153 (960.02 MB)
telemt_user_octets_to_client{user="hello"} 26820989700 (24.98 GB)
telemt_user_msgs_from_client{user="hello"} 226174
telemt_user_msgs_to_client{user="hello"} 1758108
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 42899.1 (11h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122171
telemt_connections_bad_total 1521
telemt_handshake_timeouts_total 2173
telemt_upstream_connect_attempt_total 11946
telemt_upstream_connect_success_total 11945
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6189
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 281
telemt_me_reconnect_attempts_total 10862
telemt_me_reconnect_success_total 9727
telemt_me_reader_eof_total 10333
telemt_me_idle_close_by_peer_total 10333
telemt_me_route_drop_no_conn_total 45871
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113645
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
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 9859
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 9707
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 113616
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 2473289232 (2.30 GB)
telemt_user_octets_to_client{user="hello"} 56082096260 (52.23 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 42874.4 (11h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175644
telemt_connections_bad_total 13151
telemt_handshake_timeouts_total 1251
telemt_upstream_connect_attempt_total 22634
telemt_upstream_connect_success_total 13018
telemt_upstream_connect_fail_total 9616
telemt_upstream_connect_attempts_per_request{bucket="1"} 22634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5597
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9616
telemt_me_keepalive_timeout_total 2425
telemt_me_reconnect_attempts_total 39150
telemt_me_reconnect_success_total 7968
telemt_me_reader_eof_total 9188
telemt_me_idle_close_by_peer_total 9181
telemt_me_route_drop_no_conn_total 60471
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 141109
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 481
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 341
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 9083
telemt_me_refill_failed_total 971
telemt_me_writer_restored_same_endpoint_total 7958
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1115
telemt_user_connections_total{user="hello"} 143866
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 2625316846 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 57453836505 (53.51 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 42831.1 (11h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 272541
telemt_connections_bad_total 2145
telemt_handshake_timeouts_total 2181
telemt_upstream_connect_attempt_total 9026
telemt_upstream_connect_success_total 8980
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 9026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4802
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 476
telemt_me_reconnect_attempts_total 10417
telemt_me_reconnect_success_total 6812
telemt_me_reader_eof_total 7265
telemt_me_idle_close_by_peer_total 7264
telemt_me_route_drop_no_conn_total 128313
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 271426
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 256
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 7012
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 6805
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 259737
telemt_user_connections_current{user="hello"} 428
telemt_user_octets_from_client{user="hello"} 4700354188 (4.38 GB)
telemt_user_octets_to_client{user="hello"} 126232083732 (117.56 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 57
```