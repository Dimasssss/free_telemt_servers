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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-17 06:39:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 42867.6 (11h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259673
telemt_connections_bad_total 3386
telemt_handshake_timeouts_total 8335
telemt_upstream_connect_attempt_total 8925
telemt_upstream_connect_success_total 8878
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 8925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4809
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6774
telemt_me_reconnect_success_total 6749
telemt_me_reader_eof_total 7184
telemt_me_idle_close_by_peer_total 7184
telemt_me_route_drop_no_conn_total 79426
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 232247
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1701
telemt_desync_full_logged_total 529
telemt_desync_suppressed_total 1172
telemt_desync_frames_bucket_total{bucket="1_2"} 392
telemt_desync_frames_bucket_total{bucket="3_10"} 854
telemt_desync_frames_bucket_total{bucket="gt_10"} 455
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 6818
telemt_me_writer_restored_same_endpoint_total 6728
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 232034
telemt_user_connections_current{user="hello"} 719
telemt_user_octets_from_client{user="hello"} 3086861712 (2.87 GB)
telemt_user_octets_to_client{user="hello"} 101458193580 (94.49 GB)
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 43118.9 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145734
telemt_connections_bad_total 2208
telemt_handshake_timeouts_total 11144
telemt_upstream_connect_attempt_total 11801
telemt_upstream_connect_success_total 11654
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 11801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6682
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_reconnect_attempts_total 10709
telemt_me_reconnect_success_total 9532
telemt_me_reader_eof_total 10077
telemt_me_idle_close_by_peer_total 10077
telemt_me_route_drop_no_conn_total 54006
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 126770
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 344
telemt_desync_full_logged_total 124
telemt_desync_suppressed_total 220
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 160
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 9655
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 9516
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 126779
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 1553143200 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 53743624144 (50.05 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 42895.3 (11h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87163
telemt_connections_bad_total 1110
telemt_handshake_timeouts_total 2781
telemt_upstream_connect_attempt_total 11487
telemt_upstream_connect_success_total 11427
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 11487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6306
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 9326
telemt_me_reconnect_success_total 9274
telemt_me_reader_eof_total 9927
telemt_me_idle_close_by_peer_total 9927
telemt_me_route_drop_no_conn_total 29544
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75059
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 57
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 9385
telemt_me_writer_restored_same_endpoint_total 9263
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 75041
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 6148716864 (5.73 GB)
telemt_user_octets_to_client{user="hello"} 23968909396 (22.32 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 42954.4 (11h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156215
telemt_connections_bad_total 4576
telemt_handshake_timeouts_total 7264
telemt_upstream_connect_attempt_total 9716
telemt_upstream_connect_success_total 9635
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 9716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5056
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_reconnect_attempts_total 7504
telemt_me_reconnect_success_total 7446
telemt_me_reader_eof_total 7919
telemt_me_idle_close_by_peer_total 7919
telemt_me_route_drop_no_conn_total 51516
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139723
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 260
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 182
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7554
telemt_me_writer_restored_same_endpoint_total 7439
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 139734
telemt_user_connections_current{user="hello"} 442
telemt_user_octets_from_client{user="hello"} 1506354662 (1.40 GB)
telemt_user_octets_to_client{user="hello"} 67454925221 (62.82 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 42926.4 (11h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117249
telemt_connections_bad_total 34723
telemt_handshake_timeouts_total 2374
telemt_upstream_connect_attempt_total 13059
telemt_upstream_connect_success_total 12888
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 13059
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6900
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 185
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_reconnect_attempts_total 13898
telemt_me_reconnect_success_total 10640
telemt_me_reader_eof_total 11236
telemt_me_idle_close_by_peer_total 11236
telemt_me_route_drop_no_conn_total 29808
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76952
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 53
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 10881
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 10632
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 77048
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 801438899 (764.31 MB)
telemt_user_octets_to_client{user="hello"} 35393578442 (32.96 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 43087.8 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 280646
telemt_connections_bad_total 39981
telemt_handshake_timeouts_total 2238
telemt_upstream_connect_attempt_total 8733
telemt_upstream_connect_success_total 8687
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 8733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 6588
telemt_me_reconnect_success_total 6559
telemt_me_reader_eof_total 7032
telemt_me_idle_close_by_peer_total 7032
telemt_me_route_drop_no_conn_total 224751
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 305808
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 262
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 81
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 6658
telemt_me_writer_restored_same_endpoint_total 6549
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 227744
telemt_user_connections_current{user="hello"} 722
telemt_user_octets_from_client{user="hello"} 3359526420 (3.13 GB)
telemt_user_octets_to_client{user="hello"} 155498531956 (144.82 GB)
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 31093.9 (8h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1145
telemt_connections_bad_total 192
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 15481
telemt_upstream_connect_success_total 15481
telemt_upstream_connect_attempts_per_request{bucket="1"} 15481
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6645
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 13938
telemt_me_reconnect_success_total 13862
telemt_me_reader_eof_total 15193
telemt_me_idle_close_by_peer_total 15193
telemt_me_route_drop_no_conn_total 121
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 937
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 13989
telemt_me_writer_restored_same_endpoint_total 13862
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 937
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 201161464 (191.84 MB)
telemt_user_octets_to_client{user="hello"} 12277868256 (11.43 GB)
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```