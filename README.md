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

# Server Metrics 2026-03-14 10:36:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 183784.5 (51h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 717625
telemt_connections_bad_total 33914
telemt_handshake_timeouts_total 13863
telemt_upstream_connect_attempt_total 46910
telemt_upstream_connect_success_total 46675
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 46910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6028
telemt_me_reconnect_attempts_total 42883
telemt_me_reconnect_success_total 37121
telemt_me_reader_eof_total 39700
telemt_me_idle_close_by_peer_total 39699
telemt_me_route_drop_no_conn_total 237405
telemt_me_route_drop_channel_closed_total 38
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 614665
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2423
telemt_desync_full_logged_total 814
telemt_desync_suppressed_total 1609
telemt_desync_frames_bucket_total{bucket="1_2"} 518
telemt_desync_frames_bucket_total{bucket="3_10"} 893
telemt_desync_frames_bucket_total{bucket="gt_10"} 1012
telemt_pool_swap_total 167
telemt_me_writer_removed_unexpected_total 37697
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 37101
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 576
telemt_user_connections_total{user="hello"} 614542
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 17429555166 (16.23 GB)
telemt_user_octets_to_client{user="hello"} 295018581776 (274.76 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 183677.3 (51h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 358217
telemt_connections_bad_total 2825
telemt_handshake_timeouts_total 3184
telemt_upstream_connect_attempt_total 154261
telemt_upstream_connect_success_total 152904
telemt_upstream_connect_fail_total 1357
telemt_upstream_connect_attempts_per_request{bucket="1"} 154261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38729
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2461
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1357
telemt_me_keepalive_timeout_total 5474
telemt_me_reconnect_attempts_total 188742
telemt_me_reconnect_success_total 40454
telemt_me_reader_eof_total 46156
telemt_me_idle_close_by_peer_total 46156
telemt_me_route_drop_no_conn_total 123565
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 235007
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 45
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
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 45474
telemt_me_refill_failed_total 4627
telemt_me_writer_restored_same_endpoint_total 40437
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5020
telemt_user_connections_total{user="hello"} 338111
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 3455169375 (3.22 GB)
telemt_user_octets_to_client{user="hello"} 107700993619 (100.30 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 183640.7 (51h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 415177
telemt_connections_bad_total 3268
telemt_handshake_timeouts_total 35837
telemt_upstream_connect_attempt_total 48751
telemt_upstream_connect_success_total 48741
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 48750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26371
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3915
telemt_me_reconnect_attempts_total 40858
telemt_me_reconnect_success_total 39552
telemt_me_reader_eof_total 42509
telemt_me_idle_close_by_peer_total 42509
telemt_me_route_drop_no_conn_total 150814
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 361372
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 137
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 172
telemt_me_writer_removed_unexpected_total 40027
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 39531
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 475
telemt_user_connections_total{user="hello"} 361103
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 13980645104 (13.02 GB)
telemt_user_octets_to_client{user="hello"} 158733240768 (147.83 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 183616.5 (51h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 524655
telemt_connections_bad_total 16713
telemt_handshake_timeouts_total 5234
telemt_upstream_connect_attempt_total 79126
telemt_upstream_connect_success_total 68454
telemt_upstream_connect_fail_total 10672
telemt_upstream_connect_attempts_per_request{bucket="1"} 79126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28170
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 351
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10672
telemt_me_keepalive_timeout_total 5659
telemt_me_reconnect_attempts_total 152591
telemt_me_reconnect_success_total 40292
telemt_me_reader_eof_total 45093
telemt_me_idle_close_by_peer_total 45085
telemt_me_route_drop_no_conn_total 190120
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 449172
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2014
telemt_desync_full_logged_total 596
telemt_desync_suppressed_total 1418
telemt_desync_frames_bucket_total{bucket="1_2"} 478
telemt_desync_frames_bucket_total{bucket="3_10"} 774
telemt_desync_frames_bucket_total{bucket="gt_10"} 762
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 44256
telemt_me_refill_failed_total 3501
telemt_me_writer_restored_same_endpoint_total 40282
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3964
telemt_user_connections_total{user="hello"} 468039
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 10007069279 (9.32 GB)
telemt_user_octets_to_client{user="hello"} 193374490828 (180.09 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 133787.8 (37h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223465
telemt_connections_bad_total 34683
telemt_handshake_timeouts_total 1992
telemt_upstream_connect_attempt_total 47133
telemt_upstream_connect_success_total 46667
telemt_upstream_connect_fail_total 466
telemt_upstream_connect_attempts_per_request{bucket="1"} 47133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 466
telemt_me_keepalive_timeout_total 2815
telemt_me_reconnect_attempts_total 51001
telemt_me_reconnect_success_total 35117
telemt_me_reader_eof_total 37552
telemt_me_idle_close_by_peer_total 37552
telemt_me_route_drop_no_conn_total 67662
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175919
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 759
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 572
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 361
telemt_desync_frames_bucket_total{bucket="gt_10"} 271
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 35935
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 35099
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 818
telemt_user_connections_total{user="hello"} 180676
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 2680807757 (2.50 GB)
telemt_user_octets_to_client{user="hello"} 84078670783 (78.30 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 183572.6 (50h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1064621
telemt_connections_bad_total 37046
telemt_handshake_timeouts_total 26944
telemt_upstream_connect_attempt_total 38336
telemt_upstream_connect_success_total 38134
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 38336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20057
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_keepalive_timeout_total 4876
telemt_me_reconnect_attempts_total 33760
telemt_me_reconnect_success_total 29071
telemt_me_reader_eof_total 31172
telemt_me_idle_close_by_peer_total 31169
telemt_me_route_drop_no_conn_total 498069
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 986946
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 806
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 540
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 278
telemt_pool_swap_total 171
telemt_me_writer_removed_unexpected_total 29582
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 29064
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 511
telemt_user_connections_total{user="hello"} 959559
telemt_user_connections_current{user="hello"} 533
telemt_user_octets_from_client{user="hello"} 18019308836 (16.78 GB)
telemt_user_octets_to_client{user="hello"} 482202246868 (449.09 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 81
```