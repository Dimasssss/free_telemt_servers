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

# Server Metrics 2026-03-18 07:43:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 133112.9 (36h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1837304
telemt_connections_bad_total 11802
telemt_handshake_timeouts_total 38031
telemt_upstream_connect_attempt_total 28803
telemt_upstream_connect_success_total 28279
telemt_upstream_connect_fail_total 524
telemt_upstream_connect_attempts_per_request{bucket="1"} 28803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13616
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 524
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 289
telemt_me_reconnect_attempts_total 36541
telemt_me_reconnect_success_total 19377
telemt_me_reader_eof_total 20977
telemt_me_idle_close_by_peer_total 20976
telemt_me_route_drop_no_conn_total 668675
telemt_me_route_drop_channel_closed_total 196
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1466260
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8805
telemt_desync_full_logged_total 2672
telemt_desync_suppressed_total 6133
telemt_desync_frames_bucket_total{bucket="1_2"} 2268
telemt_desync_frames_bucket_total{bucket="3_10"} 3404
telemt_desync_frames_bucket_total{bucket="gt_10"} 3133
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 20204
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 19355
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 827
telemt_user_connections_total{user="hello"} 1460522
telemt_user_connections_current{user="hello"} 1228
telemt_user_octets_from_client{user="hello"} 33561483451 (31.26 GB)
telemt_user_octets_to_client{user="hello"} 517329509459 (481.80 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 450
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 133364.0 (37h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1933889
telemt_connections_bad_total 100867
telemt_handshake_timeouts_total 60696
telemt_upstream_connect_attempt_total 472356
telemt_upstream_connect_success_total 470704
telemt_upstream_connect_fail_total 1652
telemt_upstream_connect_attempts_per_request{bucket="1"} 472356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35538
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43371
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1652
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 412
telemt_me_reconnect_attempts_total 132418
telemt_me_reconnect_success_total 21139
telemt_me_reader_eof_total 23596
telemt_me_idle_close_by_peer_total 23583
telemt_me_route_drop_no_conn_total 563678
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1240510
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5761
telemt_desync_full_logged_total 1982
telemt_desync_suppressed_total 3779
telemt_desync_frames_bucket_total{bucket="1_2"} 1083
telemt_desync_frames_bucket_total{bucket="3_10"} 2332
telemt_desync_frames_bucket_total{bucket="gt_10"} 2346
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 22921
telemt_me_refill_failed_total 3471
telemt_me_writer_restored_same_endpoint_total 21121
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1782
telemt_user_connections_total{user="hello"} 1682948
telemt_user_connections_current{user="hello"} 2723
telemt_user_octets_from_client{user="hello"} 27562836157 (25.67 GB)
telemt_user_octets_to_client{user="hello"} 660262774574 (614.92 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 863
telemt_user_unique_ips_recent_window{user="hello"} 392
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 133140.3 (36h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1453901
telemt_connections_bad_total 88426
telemt_handshake_timeouts_total 33951
telemt_upstream_connect_attempt_total 30014
telemt_upstream_connect_success_total 29847
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 30014
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15946
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 163
telemt_me_reconnect_attempts_total 43905
telemt_me_reconnect_success_total 23182
telemt_me_reader_eof_total 25172
telemt_me_idle_close_by_peer_total 25164
telemt_me_route_drop_no_conn_total 539761
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1057859
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3767
telemt_desync_full_logged_total 1265
telemt_desync_suppressed_total 2502
telemt_desync_frames_bucket_total{bucket="1_2"} 1035
telemt_desync_frames_bucket_total{bucket="3_10"} 1433
telemt_desync_frames_bucket_total{bucket="gt_10"} 1299
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 24157
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 23170
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 975
telemt_user_connections_total{user="hello"} 1055849
telemt_user_connections_current{user="hello"} 1756
telemt_user_octets_from_client{user="hello"} 49766894876 (46.35 GB)
telemt_user_octets_to_client{user="hello"} 504440644940 (469.80 GB)
telemt_user_unique_ips_current{user="hello"} 559
telemt_user_unique_ips_recent_window{user="hello"} 254
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 133199.2 (36h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1868882
telemt_connections_bad_total 86721
telemt_handshake_timeouts_total 33207
telemt_upstream_connect_attempt_total 93119
telemt_upstream_connect_success_total 90661
telemt_upstream_connect_fail_total 2458
telemt_upstream_connect_attempts_per_request{bucket="1"} 93119
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15657
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 387
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2458
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 361
telemt_me_reconnect_attempts_total 40804
telemt_me_reconnect_success_total 19281
telemt_me_reader_eof_total 21133
telemt_me_idle_close_by_peer_total 21130
telemt_me_route_drop_no_conn_total 883092
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1553378
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6100
telemt_desync_full_logged_total 1876
telemt_desync_suppressed_total 4224
telemt_desync_frames_bucket_total{bucket="1_2"} 1387
telemt_desync_frames_bucket_total{bucket="3_10"} 2513
telemt_desync_frames_bucket_total{bucket="gt_10"} 2200
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 20312
telemt_me_refill_failed_total 663
telemt_me_writer_restored_same_endpoint_total 19261
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 1031
telemt_user_connections_total{user="hello"} 1616504
telemt_user_connections_current{user="hello"} 2802
telemt_user_octets_from_client{user="hello"} 26344634958 (24.54 GB)
telemt_user_octets_to_client{user="hello"} 724532087546 (674.77 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 734
telemt_user_unique_ips_recent_window{user="hello"} 357
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 133171.1 (36h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1336093
telemt_connections_bad_total 118640
telemt_handshake_timeouts_total 14806
telemt_upstream_connect_attempt_total 49948
telemt_upstream_connect_success_total 49255
telemt_upstream_connect_fail_total 693
telemt_upstream_connect_attempts_per_request{bucket="1"} 49948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18511
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 432
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 693
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 66297
telemt_me_reconnect_success_total 26169
telemt_me_reader_eof_total 28415
telemt_me_idle_close_by_peer_total 28412
telemt_me_route_drop_no_conn_total 466562
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1104180
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4765
telemt_desync_full_logged_total 1482
telemt_desync_suppressed_total 3283
telemt_desync_frames_bucket_total{bucket="1_2"} 1234
telemt_desync_frames_bucket_total{bucket="3_10"} 1844
telemt_desync_frames_bucket_total{bucket="gt_10"} 1687
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 27828
telemt_me_refill_failed_total 1248
telemt_me_writer_restored_same_endpoint_total 26161
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1659
telemt_user_connections_total{user="hello"} 1120504
telemt_user_connections_current{user="hello"} 2298
telemt_user_octets_from_client{user="hello"} 22233274216 (20.71 GB)
telemt_user_octets_to_client{user="hello"} 556855204460 (518.61 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 703
telemt_user_unique_ips_recent_window{user="hello"} 309
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 133332.1 (37h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1310870
telemt_connections_bad_total 134715
telemt_handshake_timeouts_total 11052
telemt_upstream_connect_attempt_total 26532
telemt_upstream_connect_success_total 26374
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 26532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13537
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 279
telemt_me_reconnect_attempts_total 31037
telemt_me_reconnect_success_total 19734
telemt_me_reader_eof_total 21350
telemt_me_idle_close_by_peer_total 21347
telemt_me_route_drop_no_conn_total 864238
telemt_me_route_drop_channel_closed_total 98
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1276910
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2540
telemt_desync_full_logged_total 893
telemt_desync_suppressed_total 1647
telemt_desync_frames_bucket_total{bucket="1_2"} 551
telemt_desync_frames_bucket_total{bucket="3_10"} 983
telemt_desync_frames_bucket_total{bucket="gt_10"} 1006
telemt_pool_swap_total 120
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 20387
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 19720
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 653
telemt_user_connections_total{user="hello"} 1085565
telemt_user_connections_current{user="hello"} 919
telemt_user_octets_from_client{user="hello"} 16812964220 (15.66 GB)
telemt_user_octets_to_client{user="hello"} 473211484728 (440.71 GB)
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 81099.3 (22h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 766111
telemt_connections_bad_total 73295
telemt_handshake_timeouts_total 16217
telemt_upstream_connect_attempt_total 27154
telemt_upstream_connect_success_total 26865
telemt_upstream_connect_fail_total 289
telemt_upstream_connect_attempts_per_request{bucket="1"} 27154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12450
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 289
telemt_me_keepalive_timeout_total 149
telemt_me_reconnect_attempts_total 34310
telemt_me_reconnect_success_total 22687
telemt_me_reader_eof_total 23953
telemt_me_idle_close_by_peer_total 23953
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 223452
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 576897
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2361
telemt_desync_full_logged_total 811
telemt_desync_suppressed_total 1550
telemt_desync_frames_bucket_total{bucket="1_2"} 399
telemt_desync_frames_bucket_total{bucket="3_10"} 992
telemt_desync_frames_bucket_total{bucket="gt_10"} 970
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23296
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 22640
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 609
telemt_user_connections_total{user="hello"} 576567
telemt_user_connections_current{user="hello"} 1745
telemt_user_octets_from_client{user="hello"} 29421888537 (27.40 GB)
telemt_user_octets_to_client{user="hello"} 416147273082 (387.57 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 501
telemt_user_unique_ips_recent_window{user="hello"} 212
```