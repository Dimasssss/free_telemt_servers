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

# Server Metrics 2026-03-15 12:15:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 50436.4 (14h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219458
telemt_connections_bad_total 1522
telemt_handshake_timeouts_total 4634
telemt_upstream_connect_attempt_total 12743
telemt_upstream_connect_success_total 12674
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 12743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7052
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 13529
telemt_me_reconnect_success_total 10157
telemt_me_reader_eof_total 10859
telemt_me_idle_close_by_peer_total 10859
telemt_me_route_drop_no_conn_total 424460
telemt_me_route_drop_channel_closed_total 65
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 265935
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1527
telemt_desync_full_logged_total 606
telemt_desync_suppressed_total 921
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 611
telemt_desync_frames_bucket_total{bucket="gt_10"} 666
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 10364
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 10126
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 207
telemt_user_connections_total{user="hello"} 205047
telemt_user_connections_current{user="hello"} 351
telemt_user_octets_from_client{user="hello"} 3892120928 (3.62 GB)
telemt_user_octets_to_client{user="hello"} 192217185448 (179.02 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 50442.8 (14h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76991
telemt_connections_bad_total 2658
telemt_handshake_timeouts_total 5493
telemt_upstream_connect_attempt_total 13682
telemt_upstream_connect_success_total 13682
telemt_upstream_connect_attempts_per_request{bucket="1"} 13682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7711
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 13470
telemt_me_reconnect_success_total 11136
telemt_me_reader_eof_total 11940
telemt_me_idle_close_by_peer_total 11940
telemt_me_route_drop_no_conn_total 34758
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66391
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 11329
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 11120
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 193
telemt_user_connections_total{user="hello"} 66390
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 1198564016 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 29664309880 (27.63 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 50435.2 (14h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81107
telemt_connections_bad_total 1020
telemt_handshake_timeouts_total 2586
telemt_upstream_connect_attempt_total 14476
telemt_upstream_connect_success_total 14468
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 14476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 14067
telemt_me_reconnect_success_total 11924
telemt_me_reader_eof_total 12762
telemt_me_idle_close_by_peer_total 12762
telemt_me_route_drop_no_conn_total 31058
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73917
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 45
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 12105
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 11916
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 73831
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 9545137088 (8.89 GB)
telemt_user_octets_to_client{user="hello"} 44361284116 (41.31 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 50435.1 (14h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110306
telemt_connections_bad_total 391
telemt_handshake_timeouts_total 708
telemt_upstream_connect_attempt_total 11797
telemt_upstream_connect_success_total 11796
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6121
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9340
telemt_me_reconnect_success_total 9291
telemt_me_reader_eof_total 9914
telemt_me_idle_close_by_peer_total 9914
telemt_me_route_drop_no_conn_total 43979
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100622
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 268
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 186
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 114
telemt_desync_frames_bucket_total{bucket="gt_10"} 92
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 9393
telemt_me_writer_restored_same_endpoint_total 9280
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 100542
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 1775852980 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 55744003180 (51.92 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 25506.5 (7h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58568
telemt_connections_bad_total 15269
telemt_handshake_timeouts_total 859
telemt_upstream_connect_attempt_total 8318
telemt_upstream_connect_success_total 8258
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 8317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4510
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_reconnect_attempts_total 101205
telemt_me_reconnect_success_total 6786
telemt_me_reader_eof_total 7071
telemt_me_idle_close_by_peer_total 7071
telemt_me_route_drop_no_conn_total 20563
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41115
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 102
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 6776
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 6682
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 41252
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 607136877 (579.01 MB)
telemt_user_octets_to_client{user="hello"} 15823583151 (14.74 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 50434.3 (14h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 288256
telemt_connections_bad_total 47696
telemt_handshake_timeouts_total 2111
telemt_upstream_connect_attempt_total 10633
telemt_upstream_connect_success_total 10569
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 10633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_reconnect_attempts_total 8098
telemt_me_reconnect_success_total 8046
telemt_me_reader_eof_total 8569
telemt_me_idle_close_by_peer_total 8569
telemt_me_route_drop_no_conn_total 128211
telemt_me_route_drop_channel_closed_total 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230015
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 142
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 8115
telemt_me_writer_restored_same_endpoint_total 8019
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 228374
telemt_user_connections_current{user="hello"} 589
telemt_user_octets_from_client{user="hello"} 4924282912 (4.59 GB)
telemt_user_octets_to_client{user="hello"} 110948924568 (103.33 GB)
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 81
```