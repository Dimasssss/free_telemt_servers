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

# Server Metrics 2026-03-16 11:03:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 132525.6 (36h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 711754
telemt_connections_bad_total 53816
telemt_handshake_timeouts_total 22976
telemt_upstream_connect_attempt_total 30816
telemt_upstream_connect_success_total 30668
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 30816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16938
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 38105
telemt_me_reconnect_success_total 24072
telemt_me_reader_eof_total 25984
telemt_me_idle_close_by_peer_total 25984
telemt_me_route_drop_no_conn_total 595988
telemt_me_route_drop_channel_closed_total 88
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 655859
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3004
telemt_desync_full_logged_total 1157
telemt_desync_suppressed_total 1847
telemt_desync_frames_bucket_total{bucket="1_2"} 661
telemt_desync_frames_bucket_total{bucket="3_10"} 1157
telemt_desync_frames_bucket_total{bucket="gt_10"} 1186
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24768
telemt_me_refill_failed_total 434
telemt_me_writer_restored_same_endpoint_total 24037
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 696
telemt_user_connections_total{user="hello"} 592396
telemt_user_connections_current{user="hello"} 603
telemt_user_octets_from_client{user="hello"} 11445279572 (10.66 GB)
telemt_user_octets_to_client{user="hello"} 351382823396 (327.25 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 132532.5 (36h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 282880
telemt_connections_bad_total 3800
telemt_handshake_timeouts_total 16542
telemt_upstream_connect_attempt_total 35544
telemt_upstream_connect_success_total 35442
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 35544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19299
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 816
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 1632
telemt_me_reconnect_attempts_total 38571
telemt_me_reconnect_success_total 28229
telemt_me_reader_eof_total 30277
telemt_me_idle_close_by_peer_total 30276
telemt_me_route_drop_no_conn_total 138270
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 251985
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 222
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 150
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 83
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 28952
telemt_me_refill_failed_total 314
telemt_me_writer_restored_same_endpoint_total 28213
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 723
telemt_user_connections_total{user="hello"} 251704
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 5303840613 (4.94 GB)
telemt_user_octets_to_client{user="hello"} 130708478140 (121.73 GB)
telemt_user_msgs_from_client{user="hello"} 994
telemt_user_msgs_to_client{user="hello"} 1709
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 132525.4 (36h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 282358
telemt_connections_bad_total 5790
telemt_handshake_timeouts_total 7319
telemt_upstream_connect_attempt_total 36920
telemt_upstream_connect_success_total 36912
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 36920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15993
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20864
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 37667
telemt_me_reconnect_success_total 30237
telemt_me_reader_eof_total 32469
telemt_me_idle_close_by_peer_total 32468
telemt_me_route_drop_no_conn_total 97326
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 229919
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 113
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 30773
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 30229
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 536
telemt_user_connections_total{user="hello"} 229565
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 18756186745 (17.47 GB)
telemt_user_octets_to_client{user="hello"} 125749925264 (117.11 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 132525.2 (36h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 418173
telemt_connections_bad_total 1423
telemt_handshake_timeouts_total 3906
telemt_upstream_connect_attempt_total 30601
telemt_upstream_connect_success_total 30558
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 30601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15626
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 28939
telemt_me_reconnect_success_total 23941
telemt_me_reader_eof_total 25657
telemt_me_idle_close_by_peer_total 25656
telemt_me_route_drop_no_conn_total 144423
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 387823
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1430
telemt_desync_full_logged_total 481
telemt_desync_suppressed_total 949
telemt_desync_frames_bucket_total{bucket="1_2"} 283
telemt_desync_frames_bucket_total{bucket="3_10"} 610
telemt_desync_frames_bucket_total{bucket="gt_10"} 537
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 24418
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 23930
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 477
telemt_user_connections_total{user="hello"} 387691
telemt_user_connections_current{user="hello"} 462
telemt_user_octets_from_client{user="hello"} 6241669606 (5.81 GB)
telemt_user_octets_to_client{user="hello"} 150898254952 (140.53 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 107596.4 (29h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 262064
telemt_connections_bad_total 44924
telemt_handshake_timeouts_total 4362
telemt_upstream_connect_attempt_total 30712
telemt_upstream_connect_success_total 30546
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 30712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16880
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 119532
telemt_me_reconnect_success_total 25019
telemt_me_reader_eof_total 26549
telemt_me_idle_close_by_peer_total 26549
telemt_me_route_drop_no_conn_total 80181
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 204661
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 682
telemt_desync_full_logged_total 163
telemt_desync_suppressed_total 519
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 274
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 25232
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 24915
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 213
telemt_user_connections_total{user="hello"} 204282
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 2613957165 (2.43 GB)
telemt_user_octets_to_client{user="hello"} 90334782419 (84.13 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 132524.5 (36h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 925309
telemt_connections_bad_total 73473
telemt_handshake_timeouts_total 10950
telemt_upstream_connect_attempt_total 27983
telemt_upstream_connect_success_total 27836
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 27983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14648
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 23826
telemt_me_reconnect_success_total 21213
telemt_me_reader_eof_total 22653
telemt_me_idle_close_by_peer_total 22652
telemt_me_route_drop_no_conn_total 688680
telemt_me_route_drop_channel_closed_total 125
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 908871
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 502
telemt_desync_full_logged_total 147
telemt_desync_suppressed_total 355
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 170
telemt_desync_frames_bucket_total{bucket="gt_10"} 156
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 21548
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 21186
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 335
telemt_user_connections_total{user="hello"} 767490
telemt_user_connections_current{user="hello"} 759
telemt_user_octets_from_client{user="hello"} 16112999412 (15.01 GB)
telemt_user_octets_to_client{user="hello"} 447873689712 (417.11 GB)
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 108
```