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

# Server Metrics 2026-03-16 10:53:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 131904.7 (36h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 695685
telemt_connections_bad_total 44867
telemt_handshake_timeouts_total 22896
telemt_upstream_connect_attempt_total 30726
telemt_upstream_connect_success_total 30579
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 30726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16892
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 36879
telemt_me_reconnect_success_total 24030
telemt_me_reader_eof_total 25905
telemt_me_idle_close_by_peer_total 25905
telemt_me_route_drop_no_conn_total 594238
telemt_me_route_drop_channel_closed_total 88
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 649142
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2956
telemt_desync_full_logged_total 1146
telemt_desync_suppressed_total 1810
telemt_desync_frames_bucket_total{bucket="1_2"} 654
telemt_desync_frames_bucket_total{bucket="3_10"} 1130
telemt_desync_frames_bucket_total{bucket="gt_10"} 1172
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24689
telemt_me_refill_failed_total 397
telemt_me_writer_restored_same_endpoint_total 23995
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 659
telemt_user_connections_total{user="hello"} 585684
telemt_user_connections_current{user="hello"} 531
telemt_user_octets_from_client{user="hello"} 11147344984 (10.38 GB)
telemt_user_octets_to_client{user="hello"} 349473727436 (325.47 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 131921.9 (36h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 276159
telemt_connections_bad_total 3798
telemt_handshake_timeouts_total 15722
telemt_upstream_connect_attempt_total 35206
telemt_upstream_connect_success_total 35131
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 35206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19254
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 725
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 38495
telemt_me_reconnect_success_total 28167
telemt_me_reader_eof_total 30213
telemt_me_idle_close_by_peer_total 30212
telemt_me_route_drop_no_conn_total 129944
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 247222
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 210
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 142
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 89
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 28886
telemt_me_refill_failed_total 314
telemt_me_writer_restored_same_endpoint_total 28151
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 719
telemt_user_connections_total{user="hello"} 246746
telemt_user_connections_current{user="hello"} 337
telemt_user_octets_from_client{user="hello"} 5285663217 (4.92 GB)
telemt_user_octets_to_client{user="hello"} 130143852768 (121.21 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 131904.4 (36h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279805
telemt_connections_bad_total 5787
telemt_handshake_timeouts_total 7149
telemt_upstream_connect_attempt_total 36731
telemt_upstream_connect_success_total 36723
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 36731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20765
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 37524
telemt_me_reconnect_success_total 30096
telemt_me_reader_eof_total 32324
telemt_me_idle_close_by_peer_total 32323
telemt_me_route_drop_no_conn_total 96591
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 227615
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
telemt_me_writer_removed_unexpected_total 30628
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 30088
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 532
telemt_user_connections_total{user="hello"} 227267
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 18040017325 (16.80 GB)
telemt_user_octets_to_client{user="hello"} 125083109228 (116.49 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 131904.1 (36h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 413241
telemt_connections_bad_total 1421
telemt_handshake_timeouts_total 3890
telemt_upstream_connect_attempt_total 30415
telemt_upstream_connect_success_total 30372
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 30415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15548
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 162
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 28800
telemt_me_reconnect_success_total 23802
telemt_me_reader_eof_total 25517
telemt_me_idle_close_by_peer_total 25516
telemt_me_route_drop_no_conn_total 142919
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 383082
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1415
telemt_desync_full_logged_total 476
telemt_desync_suppressed_total 939
telemt_desync_frames_bucket_total{bucket="1_2"} 283
telemt_desync_frames_bucket_total{bucket="3_10"} 601
telemt_desync_frames_bucket_total{bucket="gt_10"} 531
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 24278
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 23791
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 476
telemt_user_connections_total{user="hello"} 382951
telemt_user_connections_current{user="hello"} 508
telemt_user_octets_from_client{user="hello"} 6203059422 (5.78 GB)
telemt_user_octets_to_client{user="hello"} 149674598896 (139.40 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 106975.4 (29h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259390
telemt_connections_bad_total 44696
telemt_handshake_timeouts_total 4350
telemt_upstream_connect_attempt_total 30423
telemt_upstream_connect_success_total 30258
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 30423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16717
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 119288
telemt_me_reconnect_success_total 24777
telemt_me_reader_eof_total 26306
telemt_me_idle_close_by_peer_total 26306
telemt_me_route_drop_no_conn_total 79295
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 202506
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 674
telemt_desync_full_logged_total 159
telemt_desync_suppressed_total 515
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 270
telemt_desync_frames_bucket_total{bucket="gt_10"} 307
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 24988
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 24673
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 211
telemt_user_connections_total{user="hello"} 202118
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 2587530545 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 89581044843 (83.43 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 131903.2 (36h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 917802
telemt_connections_bad_total 73453
telemt_handshake_timeouts_total 10874
telemt_upstream_connect_attempt_total 27785
telemt_upstream_connect_success_total 27638
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 27785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14512
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 23672
telemt_me_reconnect_success_total 21062
telemt_me_reader_eof_total 22484
telemt_me_idle_close_by_peer_total 22484
telemt_me_route_drop_no_conn_total 685459
telemt_me_route_drop_channel_closed_total 124
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 901677
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 482
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 340
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 160
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 21396
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 21035
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 334
telemt_user_connections_total{user="hello"} 760299
telemt_user_connections_current{user="hello"} 708
telemt_user_octets_from_client{user="hello"} 16034049484 (14.93 GB)
telemt_user_octets_to_client{user="hello"} 445784364908 (415.17 GB)
telemt_user_unique_ips_current{user="hello"} 257
telemt_user_unique_ips_recent_window{user="hello"} 104
```