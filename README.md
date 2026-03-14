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

# Server Metrics 2026-03-14 18:46:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 19786.2 (5h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110456
telemt_connections_bad_total 15598
telemt_handshake_timeouts_total 970
telemt_upstream_connect_attempt_total 4621
telemt_upstream_connect_success_total 4619
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2347
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 179
telemt_me_reconnect_attempts_total 3633
telemt_me_reconnect_success_total 3601
telemt_me_reader_eof_total 3805
telemt_me_idle_close_by_peer_total 3805
telemt_me_route_drop_no_conn_total 38714
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89236
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 346
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 221
telemt_desync_frames_bucket_total{bucket="1_2"} 86
telemt_desync_frames_bucket_total{bucket="3_10"} 128
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3658
telemt_me_writer_restored_same_endpoint_total 3583
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 89164
telemt_user_connections_current{user="hello"} 274
telemt_user_octets_from_client{user="hello"} 1813672768 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 43873502768 (40.86 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 19784.4 (5h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44622
telemt_connections_bad_total 504
telemt_handshake_timeouts_total 865
telemt_upstream_connect_attempt_total 5245
telemt_upstream_connect_success_total 5207
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 5245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2096
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3006
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 6763
telemt_me_reconnect_success_total 4189
telemt_me_reader_eof_total 4445
telemt_me_idle_close_by_peer_total 4445
telemt_me_route_drop_no_conn_total 24089
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41649
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 4328
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 4184
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 41633
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 595214168 (567.64 MB)
telemt_user_octets_to_client{user="hello"} 17987242708 (16.75 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 19788.7 (5h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47943
telemt_connections_bad_total 374
telemt_handshake_timeouts_total 1806
telemt_upstream_connect_attempt_total 7032
telemt_upstream_connect_success_total 6958
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 7032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3611
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 175
telemt_me_reconnect_attempts_total 103481
telemt_me_reconnect_success_total 5621
telemt_me_reader_eof_total 5991
telemt_me_idle_close_by_peer_total 5991
telemt_me_route_drop_no_conn_total 18963
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43156
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 8
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 5886
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 5580
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 265
telemt_user_connections_total{user="hello"} 43221
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 2928738609 (2.73 GB)
telemt_user_octets_to_client{user="hello"} 24511689434 (22.83 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 19793.5 (5h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60960
telemt_connections_bad_total 144
telemt_handshake_timeouts_total 521
telemt_upstream_connect_attempt_total 4858
telemt_upstream_connect_success_total 4828
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 4858
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2619
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 3839
telemt_me_reconnect_success_total 3818
telemt_me_reader_eof_total 3994
telemt_me_idle_close_by_peer_total 3994
telemt_me_route_drop_no_conn_total 27395
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57651
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 494
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 369
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 202
telemt_desync_frames_bucket_total{bucket="gt_10"} 212
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3859
telemt_me_writer_restored_same_endpoint_total 3816
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 57527
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 813872624 (776.17 MB)
telemt_user_octets_to_client{user="hello"} 18134795708 (16.89 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 19786.7 (5h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45788
telemt_connections_bad_total 3821
telemt_handshake_timeouts_total 2670
telemt_upstream_connect_attempt_total 4515
telemt_upstream_connect_success_total 4464
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 4515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2466
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 9971
telemt_me_reconnect_success_total 3445
telemt_me_reader_eof_total 3773
telemt_me_idle_close_by_peer_total 3773
telemt_me_route_drop_no_conn_total 15782
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37050
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 202
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 176
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 113
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3681
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 3441
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 236
telemt_user_connections_total{user="hello"} 37041
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 592027644 (564.60 MB)
telemt_user_octets_to_client{user="hello"} 10499114984 (9.78 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 19786.7 (5h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159379
telemt_connections_bad_total 7194
telemt_handshake_timeouts_total 2525
telemt_upstream_connect_attempt_total 3929
telemt_upstream_connect_success_total 3860
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 3929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1955
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 7840
telemt_me_reconnect_success_total 2841
telemt_me_reader_eof_total 3092
telemt_me_idle_close_by_peer_total 3092
telemt_me_route_drop_no_conn_total 85145
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 144131
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3026
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 2837
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 185
telemt_user_connections_total{user="hello"} 141578
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 3224857188 (3.00 GB)
telemt_user_octets_to_client{user="hello"} 73752410928 (68.69 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 70
```