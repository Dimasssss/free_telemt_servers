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

# Server Metrics 2026-03-16 03:28:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 105253.1 (29h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 451726
telemt_connections_bad_total 5373
telemt_handshake_timeouts_total 15481
telemt_upstream_connect_attempt_total 25122
telemt_upstream_connect_success_total 25007
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 25122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11048
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13912
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 23228
telemt_me_reconnect_success_total 19806
telemt_me_reader_eof_total 21178
telemt_me_idle_close_by_peer_total 21178
telemt_me_route_drop_no_conn_total 500737
telemt_me_route_drop_channel_closed_total 81
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 474102
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2306
telemt_desync_full_logged_total 927
telemt_desync_suppressed_total 1379
telemt_desync_frames_bucket_total{bucket="1_2"} 462
telemt_desync_frames_bucket_total{bucket="3_10"} 906
telemt_desync_frames_bucket_total{bucket="gt_10"} 938
telemt_pool_swap_total 100
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20127
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 19772
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 321
telemt_user_connections_total{user="hello"} 412956
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 8504649188 (7.92 GB)
telemt_user_octets_to_client{user="hello"} 293272283948 (273.13 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 105259.5 (29h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183202
telemt_connections_bad_total 2970
telemt_handshake_timeouts_total 14635
telemt_upstream_connect_attempt_total 28677
telemt_upstream_connect_success_total 28602
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 28677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15560
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 29894
telemt_me_reconnect_success_total 22988
telemt_me_reader_eof_total 24626
telemt_me_idle_close_by_peer_total 24625
telemt_me_route_drop_no_conn_total 93048
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158948
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 23527
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 22972
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 539
telemt_user_connections_total{user="hello"} 158494
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 3470659457 (3.23 GB)
telemt_user_octets_to_client{user="hello"} 81792941132 (76.18 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 105252.3 (29h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202742
telemt_connections_bad_total 2973
telemt_handshake_timeouts_total 3943
telemt_upstream_connect_attempt_total 29738
telemt_upstream_connect_success_total 29730
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 29738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16826
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 31855
telemt_me_reconnect_success_total 24467
telemt_me_reader_eof_total 26345
telemt_me_idle_close_by_peer_total 26344
telemt_me_route_drop_no_conn_total 71868
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161594
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
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 24938
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 24459
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 471
telemt_user_connections_total{user="hello"} 161326
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 16427745237 (15.30 GB)
telemt_user_octets_to_client{user="hello"} 101540460808 (94.57 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 105252.1 (29h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 267197
telemt_connections_bad_total 1224
telemt_handshake_timeouts_total 1691
telemt_upstream_connect_attempt_total 24675
telemt_upstream_connect_success_total 24654
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 24675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12725
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 19565
telemt_me_reconnect_success_total 19450
telemt_me_reader_eof_total 20758
telemt_me_idle_close_by_peer_total 20757
telemt_me_route_drop_no_conn_total 98356
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 246984
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 882
telemt_desync_full_logged_total 313
telemt_desync_suppressed_total 569
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 382
telemt_desync_frames_bucket_total{bucket="gt_10"} 325
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 19685
telemt_me_writer_restored_same_endpoint_total 19439
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 246866
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 4232818760 (3.94 GB)
telemt_user_octets_to_client{user="hello"} 111947373076 (104.26 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 80323.4 (22h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177088
telemt_connections_bad_total 31303
telemt_handshake_timeouts_total 3108
telemt_upstream_connect_attempt_total 22919
telemt_upstream_connect_success_total 22792
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 22919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12506
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 113091
telemt_me_reconnect_success_total 18620
telemt_me_reader_eof_total 19775
telemt_me_idle_close_by_peer_total 19775
telemt_me_route_drop_no_conn_total 56014
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 138349
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 339
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 18767
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 18516
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 137985
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 1946470481 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 60518472591 (56.36 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 105251.0 (29h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 678018
telemt_connections_bad_total 58743
telemt_handshake_timeouts_total 5050
telemt_upstream_connect_attempt_total 22343
telemt_upstream_connect_success_total 22224
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 22343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11603
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 18325
telemt_me_reconnect_success_total 16993
telemt_me_reader_eof_total 18132
telemt_me_idle_close_by_peer_total 18132
telemt_me_route_drop_no_conn_total 594841
telemt_me_route_drop_channel_closed_total 96
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 702295
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 17231
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 16966
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 560973
telemt_user_connections_current{user="hello"} 291
telemt_user_octets_from_client{user="hello"} 12999752872 (12.11 GB)
telemt_user_octets_to_client{user="hello"} 345503601664 (321.78 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 43
```