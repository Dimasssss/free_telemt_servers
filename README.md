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

# Server Metrics 2026-03-14 19:01:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 20706.4 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113779
telemt_connections_bad_total 15682
telemt_handshake_timeouts_total 1014
telemt_upstream_connect_attempt_total 4819
telemt_upstream_connect_success_total 4817
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2462
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3788
telemt_me_reconnect_success_total 3755
telemt_me_reader_eof_total 3970
telemt_me_idle_close_by_peer_total 3970
telemt_me_route_drop_no_conn_total 39934
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92195
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 360
telemt_desync_full_logged_total 133
telemt_desync_suppressed_total 227
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 134
telemt_desync_frames_bucket_total{bucket="gt_10"} 134
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3813
telemt_me_writer_restored_same_endpoint_total 3737
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 92123
telemt_user_connections_current{user="hello"} 341
telemt_user_octets_from_client{user="hello"} 1840622388 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 44732576724 (41.66 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 20705.4 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46105
telemt_connections_bad_total 505
telemt_handshake_timeouts_total 871
telemt_upstream_connect_attempt_total 5448
telemt_upstream_connect_success_total 5409
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 5448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3124
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 6922
telemt_me_reconnect_success_total 4348
telemt_me_reader_eof_total 4616
telemt_me_idle_close_by_peer_total 4616
telemt_me_route_drop_no_conn_total 24670
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43080
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 4489
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 4343
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 43064
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 630379188 (601.18 MB)
telemt_user_octets_to_client{user="hello"} 18421307616 (17.16 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 20708.9 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49949
telemt_connections_bad_total 374
telemt_handshake_timeouts_total 1812
telemt_upstream_connect_attempt_total 7281
telemt_upstream_connect_success_total 7203
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 7281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3757
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 175
telemt_me_reconnect_attempts_total 103683
telemt_me_reconnect_success_total 5822
telemt_me_reader_eof_total 6204
telemt_me_idle_close_by_peer_total 6204
telemt_me_route_drop_no_conn_total 19698
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45003
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
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 6087
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 5781
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 265
telemt_user_connections_total{user="hello"} 45068
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 3090882145 (2.88 GB)
telemt_user_octets_to_client{user="hello"} 25395791818 (23.65 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 20713.6 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63598
telemt_connections_bad_total 176
telemt_handshake_timeouts_total 542
telemt_upstream_connect_attempt_total 5062
telemt_upstream_connect_success_total 5031
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 5062
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2723
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 3999
telemt_me_reconnect_success_total 3977
telemt_me_reader_eof_total 4162
telemt_me_idle_close_by_peer_total 4162
telemt_me_route_drop_no_conn_total 28294
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60093
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 519
telemt_desync_full_logged_total 130
telemt_desync_suppressed_total 389
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 210
telemt_desync_frames_bucket_total{bucket="gt_10"} 225
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 4018
telemt_me_writer_restored_same_endpoint_total 3975
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 59969
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 839753388 (800.85 MB)
telemt_user_octets_to_client{user="hello"} 18960283540 (17.66 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 20706.8 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47877
telemt_connections_bad_total 4008
telemt_handshake_timeouts_total 2997
telemt_upstream_connect_attempt_total 4722
telemt_upstream_connect_success_total 4670
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 4722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2568
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 122
telemt_me_reconnect_attempts_total 10134
telemt_me_reconnect_success_total 3608
telemt_me_reader_eof_total 3948
telemt_me_idle_close_by_peer_total 3948
telemt_me_route_drop_no_conn_total 16389
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38579
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 221
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 189
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 119
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3846
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 3604
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 38569
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 600308092 (572.50 MB)
telemt_user_octets_to_client{user="hello"} 11280052556 (10.51 GB)
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 20706.3 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166006
telemt_connections_bad_total 7208
telemt_handshake_timeouts_total 2577
telemt_upstream_connect_attempt_total 4077
telemt_upstream_connect_success_total 4004
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 4077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2020
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 97
telemt_me_reconnect_attempts_total 7941
telemt_me_reconnect_success_total 2942
telemt_me_reader_eof_total 3202
telemt_me_idle_close_by_peer_total 3202
telemt_me_route_drop_no_conn_total 89107
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150949
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
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3129
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 2938
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 147822
telemt_user_connections_current{user="hello"} 454
telemt_user_octets_from_client{user="hello"} 3296110196 (3.07 GB)
telemt_user_octets_to_client{user="hello"} 76572059620 (71.31 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 65
```