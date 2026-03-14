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

# Server Metrics 2026-03-14 20:12:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 24997.4 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130328
telemt_connections_bad_total 16036
telemt_handshake_timeouts_total 1274
telemt_upstream_connect_attempt_total 5648
telemt_upstream_connect_success_total 5646
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2886
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 189
telemt_me_reconnect_attempts_total 4400
telemt_me_reconnect_success_total 4365
telemt_me_reader_eof_total 4630
telemt_me_idle_close_by_peer_total 4630
telemt_me_route_drop_no_conn_total 46537
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 107244
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 453
telemt_desync_full_logged_total 164
telemt_desync_suppressed_total 289
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 165
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4437
telemt_me_writer_restored_same_endpoint_total 4347
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 107165
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 2317011852 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 59275919516 (55.21 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 24996.4 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52778
telemt_connections_bad_total 683
telemt_handshake_timeouts_total 953
telemt_upstream_connect_attempt_total 6456
telemt_upstream_connect_success_total 6414
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 6456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2615
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3678
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 7709
telemt_me_reconnect_success_total 5133
telemt_me_reader_eof_total 5462
telemt_me_idle_close_by_peer_total 5462
telemt_me_route_drop_no_conn_total 27740
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49151
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 5285
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 5128
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 152
telemt_user_connections_total{user="hello"} 49139
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 1298142480 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 20731820300 (19.31 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 25001.1 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59295
telemt_connections_bad_total 387
telemt_handshake_timeouts_total 1868
telemt_upstream_connect_attempt_total 8375
telemt_upstream_connect_success_total 8289
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 8375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4377
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 104552
telemt_me_reconnect_success_total 6689
telemt_me_reader_eof_total 7142
telemt_me_idle_close_by_peer_total 7142
telemt_me_route_drop_no_conn_total 22787
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53926
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 6961
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 6647
telemt_me_writer_restored_fallback_total 42
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 53991
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 3774969653 (3.52 GB)
telemt_user_octets_to_client{user="hello"} 40114836342 (37.36 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 25005.9 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75905
telemt_connections_bad_total 204
telemt_handshake_timeouts_total 576
telemt_upstream_connect_attempt_total 6170
telemt_upstream_connect_success_total 6132
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 6170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3228
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 180
telemt_me_reconnect_attempts_total 4711
telemt_me_reconnect_success_total 4686
telemt_me_reader_eof_total 4922
telemt_me_idle_close_by_peer_total 4922
telemt_me_route_drop_no_conn_total 32991
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71808
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 589
telemt_desync_full_logged_total 149
telemt_desync_suppressed_total 440
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 246
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4738
telemt_me_writer_restored_same_endpoint_total 4684
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 71856
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 1071470604 (1021.83 MB)
telemt_user_octets_to_client{user="hello"} 23249283826 (21.65 GB)
telemt_user_msgs_from_client{user="hello"} 473
telemt_user_msgs_to_client{user="hello"} 2783
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 24998.7 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55370
telemt_connections_bad_total 4832
telemt_handshake_timeouts_total 3244
telemt_upstream_connect_attempt_total 5824
telemt_upstream_connect_success_total 5759
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 5824
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2580
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3146
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 140
telemt_me_reconnect_attempts_total 11007
telemt_me_reconnect_success_total 4473
telemt_me_reader_eof_total 4877
telemt_me_idle_close_by_peer_total 4877
telemt_me_route_drop_no_conn_total 18570
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44680
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 252
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 214
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4720
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 4469
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 44667
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 1355900496 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 26025872268 (24.24 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 24998.4 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192654
telemt_connections_bad_total 7280
telemt_handshake_timeouts_total 2625
telemt_upstream_connect_attempt_total 4874
telemt_upstream_connect_success_total 4786
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 4874
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2437
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 249
telemt_me_reconnect_attempts_total 8511
telemt_me_reconnect_success_total 3505
telemt_me_reader_eof_total 3804
telemt_me_idle_close_by_peer_total 3804
telemt_me_route_drop_no_conn_total 108323
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177077
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 55
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3702
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 3501
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 197
telemt_user_connections_total{user="hello"} 173566
telemt_user_connections_current{user="hello"} 437
telemt_user_octets_from_client{user="hello"} 3764802656 (3.51 GB)
telemt_user_octets_to_client{user="hello"} 85680599328 (79.80 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 55
```