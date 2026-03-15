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

# Server Metrics 2026-03-15 15:18:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 61462.1 (17h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279577
telemt_connections_bad_total 2731
telemt_handshake_timeouts_total 8244
telemt_upstream_connect_attempt_total 15432
telemt_upstream_connect_success_total 15350
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 15432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8546
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 15644
telemt_me_reconnect_success_total 12262
telemt_me_reader_eof_total 13064
telemt_me_idle_close_by_peer_total 13064
telemt_me_route_drop_no_conn_total 445462
telemt_me_route_drop_channel_closed_total 72
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 318508
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1743
telemt_desync_full_logged_total 697
telemt_desync_suppressed_total 1046
telemt_desync_frames_bucket_total{bucket="1_2"} 314
telemt_desync_frames_bucket_total{bucket="3_10"} 685
telemt_desync_frames_bucket_total{bucket="gt_10"} 744
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 12497
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 12228
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 257612
telemt_user_connections_current{user="hello"} 332
telemt_user_octets_from_client{user="hello"} 5645654872 (5.26 GB)
telemt_user_octets_to_client{user="hello"} 218234953520 (203.25 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 61468.8 (17h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104718
telemt_connections_bad_total 2799
telemt_handshake_timeouts_total 9803
telemt_upstream_connect_attempt_total 17008
telemt_upstream_connect_success_total 17008
telemt_upstream_connect_attempts_per_request{bucket="1"} 17008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 16235
telemt_me_reconnect_success_total 13877
telemt_me_reader_eof_total 14836
telemt_me_idle_close_by_peer_total 14836
telemt_me_route_drop_no_conn_total 43886
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88911
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 14113
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 13861
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 236
telemt_user_connections_total{user="hello"} 88899
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 1810786936 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 44700281876 (41.63 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 61461.7 (17h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113799
telemt_connections_bad_total 1659
telemt_handshake_timeouts_total 2870
telemt_upstream_connect_attempt_total 18186
telemt_upstream_connect_success_total 18178
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 18186
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 22382
telemt_me_reconnect_success_total 15035
telemt_me_reader_eof_total 16155
telemt_me_idle_close_by_peer_total 16155
telemt_me_route_drop_no_conn_total 43590
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98511
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 56
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 15401
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 15027
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 366
telemt_user_connections_total{user="hello"} 98411
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 10303215596 (9.60 GB)
telemt_user_octets_to_client{user="hello"} 56910952724 (53.00 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 61461.0 (17h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150155
telemt_connections_bad_total 800
telemt_handshake_timeouts_total 944
telemt_upstream_connect_attempt_total 14781
telemt_upstream_connect_success_total 14777
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 14781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7118
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7601
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 11756
telemt_me_reconnect_success_total 11685
telemt_me_reader_eof_total 12430
telemt_me_idle_close_by_peer_total 12430
telemt_me_route_drop_no_conn_total 58452
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137655
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 494
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 333
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 224
telemt_desync_frames_bucket_total{bucket="gt_10"} 166
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 11822
telemt_me_writer_restored_same_endpoint_total 11674
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 137569
telemt_user_connections_current{user="hello"} 218
telemt_user_octets_from_client{user="hello"} 2640088340 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 65943228660 (61.41 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 36532.6 (10h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88549
telemt_connections_bad_total 21979
telemt_handshake_timeouts_total 1765
telemt_upstream_connect_attempt_total 11380
telemt_upstream_connect_success_total 11312
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 11380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6126
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 103729
telemt_me_reconnect_success_total 9297
telemt_me_reader_eof_total 9728
telemt_me_idle_close_by_peer_total 9728
telemt_me_route_drop_no_conn_total 30102
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62768
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 156
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 9325
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 9193
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 62904
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 890386105 (849.14 MB)
telemt_user_octets_to_client{user="hello"} 26914501775 (25.07 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 61461.0 (17h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 378750
telemt_connections_bad_total 49777
telemt_handshake_timeouts_total 3188
telemt_upstream_connect_attempt_total 13208
telemt_upstream_connect_success_total 13130
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 13208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6610
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 11307
telemt_me_reconnect_success_total 10012
telemt_me_reader_eof_total 10654
telemt_me_idle_close_by_peer_total 10654
telemt_me_route_drop_no_conn_total 196785
telemt_me_route_drop_channel_closed_total 43
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 323373
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 301
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 222
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 10150
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 9985
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 312246
telemt_user_connections_current{user="hello"} 588
telemt_user_octets_from_client{user="hello"} 7972484260 (7.42 GB)
telemt_user_octets_to_client{user="hello"} 164858183352 (153.54 GB)
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 67
```