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

# Server Metrics 2026-03-14 08:14:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 175240.4 (48h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 673767
telemt_connections_bad_total 32462
telemt_handshake_timeouts_total 13238
telemt_upstream_connect_attempt_total 44553
telemt_upstream_connect_success_total 44328
telemt_upstream_connect_fail_total 225
telemt_upstream_connect_attempts_per_request{bucket="1"} 44553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23890
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 225
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5735
telemt_me_reconnect_attempts_total 39919
telemt_me_reconnect_success_total 35224
telemt_me_reader_eof_total 37657
telemt_me_idle_close_by_peer_total 37656
telemt_me_route_drop_no_conn_total 222974
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 574571
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2233
telemt_desync_full_logged_total 757
telemt_desync_suppressed_total 1476
telemt_desync_frames_bucket_total{bucket="1_2"} 482
telemt_desync_frames_bucket_total{bucket="3_10"} 819
telemt_desync_frames_bucket_total{bucket="gt_10"} 932
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 35747
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 35204
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 523
telemt_user_connections_total{user="hello"} 574464
telemt_user_connections_current{user="hello"} 384
telemt_user_octets_from_client{user="hello"} 16734215610 (15.58 GB)
telemt_user_octets_to_client{user="hello"} 275319658672 (256.41 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 175133.4 (48h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 338956
telemt_connections_bad_total 2329
telemt_handshake_timeouts_total 2705
telemt_upstream_connect_attempt_total 151757
telemt_upstream_connect_success_total 150459
telemt_upstream_connect_fail_total 1297
telemt_upstream_connect_attempts_per_request{bucket="1"} 151756
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2433
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1297
telemt_me_keepalive_timeout_total 4052
telemt_me_reconnect_attempts_total 179029
telemt_me_reconnect_success_total 38428
telemt_me_reader_eof_total 43876
telemt_me_idle_close_by_peer_total 43876
telemt_me_route_drop_no_conn_total 113322
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 217492
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 43196
telemt_me_refill_failed_total 4387
telemt_me_writer_restored_same_endpoint_total 38411
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4768
telemt_user_connections_total{user="hello"} 320599
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 3308720051 (3.08 GB)
telemt_user_octets_to_client{user="hello"} 104234108355 (97.08 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 175096.9 (48h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 396416
telemt_connections_bad_total 3185
telemt_handshake_timeouts_total 35324
telemt_upstream_connect_attempt_total 46186
telemt_upstream_connect_success_total 46177
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 46186
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24987
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3506
telemt_me_reconnect_attempts_total 38705
telemt_me_reconnect_success_total 37416
telemt_me_reader_eof_total 40237
telemt_me_idle_close_by_peer_total 40237
telemt_me_route_drop_no_conn_total 143356
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 344027
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 37870
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 37395
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 343786
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 13632280244 (12.70 GB)
telemt_user_octets_to_client{user="hello"} 142176948584 (132.41 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 175072.3 (48h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 498536
telemt_connections_bad_total 16275
telemt_handshake_timeouts_total 4562
telemt_upstream_connect_attempt_total 76727
telemt_upstream_connect_success_total 66108
telemt_upstream_connect_fail_total 10619
telemt_upstream_connect_attempts_per_request{bucket="1"} 76727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26917
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 343
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10619
telemt_me_keepalive_timeout_total 5459
telemt_me_reconnect_attempts_total 146819
telemt_me_reconnect_success_total 38356
telemt_me_reader_eof_total 42974
telemt_me_idle_close_by_peer_total 42966
telemt_me_route_drop_no_conn_total 180604
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 425351
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1844
telemt_desync_full_logged_total 548
telemt_desync_suppressed_total 1296
telemt_desync_frames_bucket_total{bucket="1_2"} 433
telemt_desync_frames_bucket_total{bucket="3_10"} 706
telemt_desync_frames_bucket_total{bucket="gt_10"} 705
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 42183
telemt_me_refill_failed_total 3382
telemt_me_writer_restored_same_endpoint_total 38346
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3827
telemt_user_connections_total{user="hello"} 444227
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 9533786671 (8.88 GB)
telemt_user_octets_to_client{user="hello"} 182653973872 (170.11 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 125243.9 (34h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205139
telemt_connections_bad_total 31002
telemt_handshake_timeouts_total 1765
telemt_upstream_connect_attempt_total 43974
telemt_upstream_connect_success_total 43549
telemt_upstream_connect_fail_total 425
telemt_upstream_connect_attempts_per_request{bucket="1"} 43974
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21609
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 425
telemt_me_keepalive_timeout_total 2556
telemt_me_reconnect_attempts_total 45849
telemt_me_reconnect_success_total 32413
telemt_me_reader_eof_total 34679
telemt_me_idle_close_by_peer_total 34679
telemt_me_route_drop_no_conn_total 61343
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161854
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 701
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 335
telemt_desync_frames_bucket_total{bucket="gt_10"} 252
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 33132
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 32395
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 719
telemt_user_connections_total{user="hello"} 166614
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 2458280525 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 79206753231 (73.77 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 175028.4 (48h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1005485
telemt_connections_bad_total 36296
telemt_handshake_timeouts_total 26230
telemt_upstream_connect_attempt_total 36329
telemt_upstream_connect_success_total 36135
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 36329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19099
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_keepalive_timeout_total 4741
telemt_me_reconnect_attempts_total 32158
telemt_me_reconnect_success_total 27476
telemt_me_reader_eof_total 29485
telemt_me_idle_close_by_peer_total 29482
telemt_me_route_drop_no_conn_total 472636
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 931902
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 770
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 516
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 253
telemt_desync_frames_bucket_total{bucket="gt_10"} 260
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 27971
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 27469
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 495
telemt_user_connections_total{user="hello"} 904535
telemt_user_connections_current{user="hello"} 444
telemt_user_octets_from_client{user="hello"} 15382950112 (14.33 GB)
telemt_user_octets_to_client{user="hello"} 450875535872 (419.91 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 82
```