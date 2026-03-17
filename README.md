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

# Server Metrics 2026-03-17 04:57:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 36748.6 (10h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196531
telemt_connections_bad_total 3074
telemt_handshake_timeouts_total 7049
telemt_upstream_connect_attempt_total 7803
telemt_upstream_connect_success_total 7760
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 7803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4233
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5959
telemt_me_reconnect_success_total 5939
telemt_me_reader_eof_total 6315
telemt_me_idle_close_by_peer_total 6315
telemt_me_route_drop_no_conn_total 62350
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 178071
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1139
telemt_desync_full_logged_total 395
telemt_desync_suppressed_total 744
telemt_desync_frames_bucket_total{bucket="1_2"} 262
telemt_desync_frames_bucket_total{bucket="3_10"} 584
telemt_desync_frames_bucket_total{bucket="gt_10"} 293
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5995
telemt_me_writer_restored_same_endpoint_total 5918
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 177878
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 2523661812 (2.35 GB)
telemt_user_octets_to_client{user="hello"} 80773786520 (75.23 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 36999.8 (10h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110619
telemt_connections_bad_total 2184
telemt_handshake_timeouts_total 4009
telemt_upstream_connect_attempt_total 10280
telemt_upstream_connect_success_total 10148
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 10279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5850
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_reconnect_attempts_total 9471
telemt_me_reconnect_success_total 8300
telemt_me_reader_eof_total 8779
telemt_me_idle_close_by_peer_total 8779
telemt_me_route_drop_no_conn_total 44980
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 99928
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 274
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 180
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 78
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 8415
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 8284
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 99930
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 1344924492 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 44599775636 (41.54 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 36776.4 (10h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70533
telemt_connections_bad_total 987
telemt_handshake_timeouts_total 2417
telemt_upstream_connect_attempt_total 9866
telemt_upstream_connect_success_total 9813
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 9865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5394
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 8018
telemt_me_reconnect_success_total 7974
telemt_me_reader_eof_total 8528
telemt_me_idle_close_by_peer_total 8528
telemt_me_route_drop_no_conn_total 23482
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60154
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 42
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 8074
telemt_me_writer_restored_same_endpoint_total 7963
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 60138
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 5911520232 (5.51 GB)
telemt_user_octets_to_client{user="hello"} 19423290248 (18.09 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 36835.3 (10h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114928
telemt_connections_bad_total 3629
telemt_handshake_timeouts_total 3120
telemt_upstream_connect_attempt_total 8426
telemt_upstream_connect_success_total 8355
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 8426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3906
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4394
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_reconnect_attempts_total 6529
telemt_me_reconnect_success_total 6480
telemt_me_reader_eof_total 6898
telemt_me_idle_close_by_peer_total 6898
telemt_me_route_drop_no_conn_total 38655
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104788
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 182
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 123
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 6576
telemt_me_writer_restored_same_endpoint_total 6473
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 104806
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 1148306346 (1.07 GB)
telemt_user_octets_to_client{user="hello"} 48648118225 (45.31 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 36807.2 (10h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85952
telemt_connections_bad_total 22037
telemt_handshake_timeouts_total 1416
telemt_upstream_connect_attempt_total 10876
telemt_upstream_connect_success_total 10741
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 10876
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5790
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_reconnect_attempts_total 11167
telemt_me_reconnect_success_total 8915
telemt_me_reader_eof_total 9416
telemt_me_idle_close_by_peer_total 9416
telemt_me_route_drop_no_conn_total 23792
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60248
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 9104
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 8907
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 60242
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 673904156 (642.69 MB)
telemt_user_octets_to_client{user="hello"} 24747527184 (23.05 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 36968.5 (10h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218863
telemt_connections_bad_total 29446
telemt_handshake_timeouts_total 1460
telemt_upstream_connect_attempt_total 7639
telemt_upstream_connect_success_total 7598
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 7639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3951
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 5777
telemt_me_reconnect_success_total 5752
telemt_me_reader_eof_total 6171
telemt_me_idle_close_by_peer_total 6171
telemt_me_route_drop_no_conn_total 194238
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 259249
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 177
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 5836
telemt_me_writer_restored_same_endpoint_total 5742
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 181501
telemt_user_connections_current{user="hello"} 466
telemt_user_octets_from_client{user="hello"} 2819014020 (2.63 GB)
telemt_user_octets_to_client{user="hello"} 141039006316 (131.35 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 24974.7 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183
telemt_connections_bad_total 122
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 12573
telemt_upstream_connect_success_total 12573
telemt_upstream_connect_attempts_per_request{bucket="1"} 12573
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5265
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 11335
telemt_me_reconnect_success_total 11273
telemt_me_reader_eof_total 12381
telemt_me_idle_close_by_peer_total 12381
telemt_me_route_drop_no_conn_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 11379
telemt_me_writer_restored_same_endpoint_total 11273
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 157584760 (150.28 MB)
telemt_user_octets_to_client{user="hello"} 24357516 (23.23 MB)
```