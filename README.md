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

# Server Metrics 2026-03-15 20:14:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 79226.3 (22h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 372377
telemt_connections_bad_total 4495
telemt_handshake_timeouts_total 13646
telemt_upstream_connect_attempt_total 18961
telemt_upstream_connect_success_total 18867
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 18961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10472
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 18336
telemt_me_reconnect_success_total 14935
telemt_me_reader_eof_total 15919
telemt_me_idle_close_by_peer_total 15919
telemt_me_route_drop_no_conn_total 477258
telemt_me_route_drop_channel_closed_total 78
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 401142
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1962
telemt_desync_full_logged_total 770
telemt_desync_suppressed_total 1192
telemt_desync_frames_bucket_total{bucket="1_2"} 373
telemt_desync_frames_bucket_total{bucket="3_10"} 761
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 15205
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 14901
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 340202
telemt_user_connections_current{user="hello"} 307
telemt_user_octets_from_client{user="hello"} 7620501916 (7.10 GB)
telemt_user_octets_to_client{user="hello"} 260501023088 (242.61 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 79234.2 (22h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153240
telemt_connections_bad_total 2860
telemt_handshake_timeouts_total 13295
telemt_upstream_connect_attempt_total 21698
telemt_upstream_connect_success_total 21646
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 21697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11722
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 550
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 1121
telemt_me_reconnect_attempts_total 19784
telemt_me_reconnect_success_total 17327
telemt_me_reader_eof_total 18458
telemt_me_idle_close_by_peer_total 18457
telemt_me_route_drop_no_conn_total 63827
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130609
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 17667
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 17311
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 340
telemt_user_connections_total{user="hello"} 130881
telemt_user_connections_current{user="hello"} 286
telemt_user_octets_from_client{user="hello"} 2422245649 (2.26 GB)
telemt_user_octets_to_client{user="hello"} 65755096132 (61.24 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 79225.2 (22h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153197
telemt_connections_bad_total 1729
telemt_handshake_timeouts_total 3382
telemt_upstream_connect_attempt_total 22747
telemt_upstream_connect_success_total 22739
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 22747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 26114
telemt_me_reconnect_success_total 18749
telemt_me_reader_eof_total 20128
telemt_me_idle_close_by_peer_total 20128
telemt_me_route_drop_no_conn_total 60548
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 135774
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 19164
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 18741
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 415
telemt_user_connections_total{user="hello"} 135661
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 10881803912 (10.13 GB)
telemt_user_octets_to_client{user="hello"} 77240627740 (71.94 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 79225.2 (22h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220482
telemt_connections_bad_total 1177
telemt_handshake_timeouts_total 1575
telemt_upstream_connect_attempt_total 18517
telemt_upstream_connect_success_total 18501
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 18517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9557
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 14659
telemt_me_reconnect_success_total 14570
telemt_me_reader_eof_total 15518
telemt_me_idle_close_by_peer_total 15518
telemt_me_route_drop_no_conn_total 81045
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 202885
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 751
telemt_desync_full_logged_total 269
telemt_desync_suppressed_total 482
telemt_desync_frames_bucket_total{bucket="1_2"} 148
telemt_desync_frames_bucket_total{bucket="3_10"} 337
telemt_desync_frames_bucket_total{bucket="gt_10"} 266
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 14745
telemt_me_writer_restored_same_endpoint_total 14559
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 202803
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 3774622572 (3.52 GB)
telemt_user_octets_to_client{user="hello"} 91670766812 (85.38 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 54296.5 (15h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132373
telemt_connections_bad_total 26211
telemt_handshake_timeouts_total 2504
telemt_upstream_connect_attempt_total 15930
telemt_upstream_connect_success_total 15831
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 15930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7211
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8525
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 107381
telemt_me_reconnect_success_total 12929
telemt_me_reader_eof_total 13606
telemt_me_idle_close_by_peer_total 13606
telemt_me_route_drop_no_conn_total 44852
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100027
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 309
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 242
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 114
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 13016
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 12825
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 100157
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 1603223285 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 38926769979 (36.25 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 79224.4 (22h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 538595
telemt_connections_bad_total 58381
telemt_handshake_timeouts_total 4296
telemt_upstream_connect_attempt_total 16814
telemt_upstream_connect_success_total 16719
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 16814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8662
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 14070
telemt_me_reconnect_success_total 12760
telemt_me_reader_eof_total 13562
telemt_me_idle_close_by_peer_total 13562
telemt_me_route_drop_no_conn_total 393434
telemt_me_route_drop_channel_closed_total 92
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 528505
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 323
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 12938
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 12733
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 455847
telemt_user_connections_current{user="hello"} 574
telemt_user_octets_from_client{user="hello"} 11621261348 (10.82 GB)
telemt_user_octets_to_client{user="hello"} 262111675192 (244.11 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 57
```