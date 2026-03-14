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

# Server Metrics 2026-03-14 19:06:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 21013.1 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114897
telemt_connections_bad_total 15707
telemt_handshake_timeouts_total 1058
telemt_upstream_connect_attempt_total 4921
telemt_upstream_connect_success_total 4919
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2510
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3847
telemt_me_reconnect_success_total 3814
telemt_me_reader_eof_total 4039
telemt_me_idle_close_by_peer_total 4039
telemt_me_route_drop_no_conn_total 40471
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93211
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 365
telemt_desync_full_logged_total 134
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 134
telemt_desync_frames_bucket_total{bucket="gt_10"} 139
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3874
telemt_me_writer_restored_same_endpoint_total 3796
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 93139
telemt_user_connections_current{user="hello"} 307
telemt_user_octets_from_client{user="hello"} 1860489472 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 45374859156 (42.26 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 21011.1 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46603
telemt_connections_bad_total 505
telemt_handshake_timeouts_total 871
telemt_upstream_connect_attempt_total 5561
telemt_upstream_connect_success_total 5522
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 5561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2227
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3184
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 6992
telemt_me_reconnect_success_total 4418
telemt_me_reader_eof_total 4695
telemt_me_idle_close_by_peer_total 4695
telemt_me_route_drop_no_conn_total 24842
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43552
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 4559
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 4413
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 43536
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 633631380 (604.28 MB)
telemt_user_octets_to_client{user="hello"} 18565275232 (17.29 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 21015.9 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50522
telemt_connections_bad_total 384
telemt_handshake_timeouts_total 1813
telemt_upstream_connect_attempt_total 7404
telemt_upstream_connect_success_total 7325
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 7404
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3819
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 179
telemt_me_reconnect_attempts_total 103762
telemt_me_reconnect_success_total 5900
telemt_me_reader_eof_total 6298
telemt_me_idle_close_by_peer_total 6298
telemt_me_route_drop_no_conn_total 19858
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45541
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
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 6165
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 5859
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 265
telemt_user_connections_total{user="hello"} 45605
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 3095033697 (2.88 GB)
telemt_user_octets_to_client{user="hello"} 25627867466 (23.87 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 21020.3 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64551
telemt_connections_bad_total 177
telemt_handshake_timeouts_total 543
telemt_upstream_connect_attempt_total 5179
telemt_upstream_connect_success_total 5147
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 5179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2344
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2781
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 4072
telemt_me_reconnect_success_total 4050
telemt_me_reader_eof_total 4246
telemt_me_idle_close_by_peer_total 4246
telemt_me_route_drop_no_conn_total 28591
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61006
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
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 4092
telemt_me_writer_restored_same_endpoint_total 4048
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 60882
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 845111528 (805.96 MB)
telemt_user_octets_to_client{user="hello"} 19365654004 (18.04 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 21013.4 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48441
telemt_connections_bad_total 4065
telemt_handshake_timeouts_total 3098
telemt_upstream_connect_attempt_total 4843
telemt_upstream_connect_success_total 4787
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 4843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2622
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 10208
telemt_me_reconnect_success_total 3681
telemt_me_reader_eof_total 4031
telemt_me_idle_close_by_peer_total 4031
telemt_me_route_drop_no_conn_total 16521
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38984
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 239
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 204
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 126
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3920
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 3677
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 239
telemt_user_connections_total{user="hello"} 38973
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 602283152 (574.38 MB)
telemt_user_octets_to_client{user="hello"} 11456883572 (10.67 GB)
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 21013.0 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168121
telemt_connections_bad_total 7208
telemt_handshake_timeouts_total 2580
telemt_upstream_connect_attempt_total 4169
telemt_upstream_connect_success_total 4096
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 4169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2065
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 7990
telemt_me_reconnect_success_total 2991
telemt_me_reader_eof_total 3256
telemt_me_idle_close_by_peer_total 3256
telemt_me_route_drop_no_conn_total 90479
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153001
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
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3178
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 2987
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 149874
telemt_user_connections_current{user="hello"} 510
telemt_user_octets_from_client{user="hello"} 3320323476 (3.09 GB)
telemt_user_octets_to_client{user="hello"} 77124987228 (71.83 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 69
```