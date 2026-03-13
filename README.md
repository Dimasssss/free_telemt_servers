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

# Server Metrics 2026-03-13 08:45:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 90706.7 (25h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 353553
telemt_connections_bad_total 3179
telemt_handshake_timeouts_total 7744
telemt_upstream_connect_attempt_total 22726
telemt_upstream_connect_success_total 22619
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 22726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10189
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12382
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1672
telemt_me_reconnect_attempts_total 21585
telemt_me_reconnect_success_total 18077
telemt_me_reader_eof_total 19318
telemt_me_idle_close_by_peer_total 19317
telemt_me_route_drop_no_conn_total 110615
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 302028
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 979
telemt_desync_full_logged_total 363
telemt_desync_suppressed_total 616
telemt_desync_frames_bucket_total{bucket="1_2"} 201
telemt_desync_frames_bucket_total{bucket="3_10"} 357
telemt_desync_frames_bucket_total{bucket="gt_10"} 421
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 18375
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 18061
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 298
telemt_user_connections_total{user="hello"} 301719
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 4938335700 (4.60 GB)
telemt_user_octets_to_client{user="hello"} 137591125312 (128.14 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 90599.6 (25h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160745
telemt_connections_bad_total 1503
telemt_handshake_timeouts_total 1210
telemt_upstream_connect_attempt_total 45601
telemt_upstream_connect_success_total 44982
telemt_upstream_connect_fail_total 619
telemt_upstream_connect_attempts_per_request{bucket="1"} 45601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18312
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 513
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 619
telemt_me_keepalive_timeout_total 696
telemt_me_reconnect_attempts_total 79337
telemt_me_reconnect_success_total 23966
telemt_me_reader_eof_total 26403
telemt_me_idle_close_by_peer_total 26403
telemt_me_route_drop_no_conn_total 61221
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 135102
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 25891
telemt_me_refill_failed_total 1728
telemt_me_writer_restored_same_endpoint_total 23951
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1925
telemt_user_connections_total{user="hello"} 151596
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 1570678416 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 48678323755 (45.34 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 90563.1 (25h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194379
telemt_connections_bad_total 1999
telemt_handshake_timeouts_total 3467
telemt_upstream_connect_attempt_total 24592
telemt_upstream_connect_success_total 24588
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 24591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13277
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 583
telemt_me_reconnect_attempts_total 21210
telemt_me_reconnect_success_total 20025
telemt_me_reader_eof_total 21477
telemt_me_idle_close_by_peer_total 21477
telemt_me_route_drop_no_conn_total 74274
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 181761
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 20247
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 20005
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 181687
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 6729266328 (6.27 GB)
telemt_user_octets_to_client{user="hello"} 75996472268 (70.78 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 90538.8 (25h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 281188
telemt_connections_bad_total 13662
telemt_handshake_timeouts_total 2113
telemt_upstream_connect_attempt_total 37546
telemt_upstream_connect_success_total 27568
telemt_upstream_connect_fail_total 9978
telemt_upstream_connect_attempts_per_request{bucket="1"} 37546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13636
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 182
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9978
telemt_me_keepalive_timeout_total 3387
telemt_me_reconnect_attempts_total 72853
telemt_me_reconnect_success_total 20187
telemt_me_reader_eof_total 22467
telemt_me_idle_close_by_peer_total 22460
telemt_me_route_drop_no_conn_total 101407
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 239312
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 886
telemt_desync_full_logged_total 262
telemt_desync_suppressed_total 624
telemt_desync_frames_bucket_total{bucket="1_2"} 225
telemt_desync_frames_bucket_total{bucket="3_10"} 327
telemt_desync_frames_bucket_total{bucket="gt_10"} 334
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 22089
telemt_me_refill_failed_total 1641
telemt_me_writer_restored_same_endpoint_total 20177
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1902
telemt_user_connections_total{user="hello"} 242037
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 5384988022 (5.02 GB)
telemt_user_octets_to_client{user="hello"} 92446943613 (86.10 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 40710.2 (11h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51737
telemt_connections_bad_total 8255
telemt_handshake_timeouts_total 434
telemt_upstream_connect_attempt_total 14177
telemt_upstream_connect_success_total 14033
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 14177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7807
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 330
telemt_me_reconnect_attempts_total 14196
telemt_me_reconnect_success_total 11976
telemt_me_reader_eof_total 12766
telemt_me_idle_close_by_peer_total 12766
telemt_me_route_drop_no_conn_total 15606
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41620
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 71
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 62
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 12148
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 11958
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 41619
telemt_user_connections_current{user="hello"} 50
telemt_user_octets_from_client{user="hello"} 299738960 (285.85 MB)
telemt_user_octets_to_client{user="hello"} 11585537728 (10.79 GB)
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 90495.3 (25h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 482879
telemt_connections_bad_total 13366
telemt_handshake_timeouts_total 4537
telemt_upstream_connect_attempt_total 19124
telemt_upstream_connect_success_total 19020
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 19123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10099
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 1537
telemt_me_reconnect_attempts_total 18169
telemt_me_reconnect_success_total 14526
telemt_me_reader_eof_total 15603
telemt_me_idle_close_by_peer_total 15600
telemt_me_route_drop_no_conn_total 252298
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 474528
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 392
telemt_desync_full_logged_total 149
telemt_desync_suppressed_total 243
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 141
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 14827
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 14519
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 301
telemt_user_connections_total{user="hello"} 447831
telemt_user_connections_current{user="hello"} 407
telemt_user_octets_from_client{user="hello"} 8233899832 (7.67 GB)
telemt_user_octets_to_client{user="hello"} 254782391156 (237.28 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 57
```