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

# Server Metrics 2026-03-17 17:22:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 81448.2 (22h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 976083
telemt_connections_bad_total 6524
telemt_handshake_timeouts_total 27703
telemt_upstream_connect_attempt_total 19305
telemt_upstream_connect_success_total 18827
telemt_upstream_connect_fail_total 478
telemt_upstream_connect_attempts_per_request{bucket="1"} 19305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8847
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 478
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 170
telemt_me_reconnect_attempts_total 29553
telemt_me_reconnect_success_total 12437
telemt_me_reader_eof_total 13550
telemt_me_idle_close_by_peer_total 13549
telemt_me_route_drop_no_conn_total 446936
telemt_me_route_drop_channel_closed_total 122
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 892389
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5957
telemt_desync_full_logged_total 1686
telemt_desync_suppressed_total 4271
telemt_desync_frames_bucket_total{bucket="1_2"} 1655
telemt_desync_frames_bucket_total{bucket="3_10"} 2300
telemt_desync_frames_bucket_total{bucket="gt_10"} 2002
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 13145
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 12415
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 708
telemt_user_connections_total{user="hello"} 886652
telemt_user_connections_current{user="hello"} 1169
telemt_user_octets_from_client{user="hello"} 13642483427 (12.71 GB)
telemt_user_octets_to_client{user="hello"} 301183423407 (280.50 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 369
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 81700.1 (22h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 809391
telemt_connections_bad_total 48832
telemt_handshake_timeouts_total 30719
telemt_upstream_connect_attempt_total 304868
telemt_upstream_connect_success_total 304135
telemt_upstream_connect_fail_total 724
telemt_upstream_connect_attempts_per_request{bucket="1"} 304859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 251917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23559
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28657
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 724
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 49834
telemt_me_reconnect_success_total 13565
telemt_me_reader_eof_total 15251
telemt_me_idle_close_by_peer_total 15251
telemt_me_route_drop_no_conn_total 231805
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 407565
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1536
telemt_desync_full_logged_total 486
telemt_desync_suppressed_total 1050
telemt_desync_frames_bucket_total{bucket="1_2"} 346
telemt_desync_frames_bucket_total{bucket="3_10"} 671
telemt_desync_frames_bucket_total{bucket="gt_10"} 519
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14861
telemt_me_refill_failed_total 1129
telemt_me_writer_restored_same_endpoint_total 13549
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1296
telemt_user_connections_total{user="hello"} 693938
telemt_user_connections_current{user="hello"} 2191
telemt_user_octets_from_client{user="hello"} 9191180401 (8.56 GB)
telemt_user_octets_to_client{user="hello"} 188618771030 (175.66 GB)
telemt_user_msgs_from_client{user="hello"} 4749053
telemt_user_msgs_to_client{user="hello"} 19841331
telemt_user_unique_ips_current{user="hello"} 479
telemt_user_unique_ips_recent_window{user="hello"} 293
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 81476.0 (22h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 414705
telemt_connections_bad_total 13086
telemt_handshake_timeouts_total 20524
telemt_upstream_connect_attempt_total 20505
telemt_upstream_connect_success_total 20388
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 20505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11041
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 36911
telemt_me_reconnect_success_total 16244
telemt_me_reader_eof_total 17773
telemt_me_idle_close_by_peer_total 17766
telemt_me_route_drop_no_conn_total 200179
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 360674
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1044
telemt_desync_full_logged_total 317
telemt_desync_suppressed_total 727
telemt_desync_frames_bucket_total{bucket="1_2"} 352
telemt_desync_frames_bucket_total{bucket="3_10"} 452
telemt_desync_frames_bucket_total{bucket="gt_10"} 240
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 17106
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16232
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 862
telemt_user_connections_total{user="hello"} 358836
telemt_user_connections_current{user="hello"} 1458
telemt_user_octets_from_client{user="hello"} 24064190988 (22.41 GB)
telemt_user_octets_to_client{user="hello"} 124905074112 (116.33 GB)
telemt_user_unique_ips_current{user="hello"} 378
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 81535.4 (22h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 878465
telemt_connections_bad_total 19584
telemt_handshake_timeouts_total 16454
telemt_upstream_connect_attempt_total 80266
telemt_upstream_connect_success_total 79872
telemt_upstream_connect_fail_total 394
telemt_upstream_connect_attempts_per_request{bucket="1"} 80266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10837
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 325
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 394
telemt_me_keepalive_timeout_total 221
telemt_me_reconnect_attempts_total 32698
telemt_me_reconnect_success_total 12400
telemt_me_reader_eof_total 13695
telemt_me_idle_close_by_peer_total 13694
telemt_me_route_drop_no_conn_total 374531
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 700326
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2249
telemt_desync_full_logged_total 723
telemt_desync_suppressed_total 1526
telemt_desync_frames_bucket_total{bucket="1_2"} 534
telemt_desync_frames_bucket_total{bucket="3_10"} 1008
telemt_desync_frames_bucket_total{bucket="gt_10"} 707
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 13254
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12391
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 854
telemt_user_connections_total{user="hello"} 763453
telemt_user_connections_current{user="hello"} 1865
telemt_user_octets_from_client{user="hello"} 9301705359 (8.66 GB)
telemt_user_octets_to_client{user="hello"} 243561516985 (226.83 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 466
telemt_user_unique_ips_recent_window{user="hello"} 232
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 81507.0 (22h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 452899
telemt_connections_bad_total 71452
telemt_handshake_timeouts_total 4372
telemt_upstream_connect_attempt_total 38646
telemt_upstream_connect_success_total 38146
telemt_upstream_connect_fail_total 500
telemt_upstream_connect_attempts_per_request{bucket="1"} 38646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12782
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 500
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 50036
telemt_me_reconnect_success_total 17558
telemt_me_reader_eof_total 19172
telemt_me_idle_close_by_peer_total 19170
telemt_me_route_drop_no_conn_total 132973
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 341005
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1514
telemt_desync_full_logged_total 365
telemt_desync_suppressed_total 1149
telemt_desync_frames_bucket_total{bucket="1_2"} 642
telemt_desync_frames_bucket_total{bucket="3_10"} 605
telemt_desync_frames_bucket_total{bucket="gt_10"} 267
telemt_pool_swap_total 37
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18864
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 17550
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1306
telemt_user_connections_total{user="hello"} 357704
telemt_user_connections_current{user="hello"} 1804
telemt_user_octets_from_client{user="hello"} 5934763676 (5.53 GB)
telemt_user_octets_to_client{user="hello"} 157645230020 (146.82 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 457
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 81669.8 (22h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 824946
telemt_connections_bad_total 60370
telemt_handshake_timeouts_total 7838
telemt_upstream_connect_attempt_total 16446
telemt_upstream_connect_success_total 16355
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 16446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8452
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 23524
telemt_me_reconnect_success_total 12255
telemt_me_reader_eof_total 13340
telemt_me_idle_close_by_peer_total 13338
telemt_me_route_drop_no_conn_total 618370
telemt_me_route_drop_channel_closed_total 72
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 850710
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1497
telemt_desync_full_logged_total 520
telemt_desync_suppressed_total 977
telemt_desync_frames_bucket_total{bucket="1_2"} 353
telemt_desync_frames_bucket_total{bucket="3_10"} 585
telemt_desync_frames_bucket_total{bucket="gt_10"} 559
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 12814
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 12241
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 559
telemt_user_connections_total{user="hello"} 713779
telemt_user_connections_current{user="hello"} 905
telemt_user_octets_from_client{user="hello"} 10546411272 (9.82 GB)
telemt_user_octets_to_client{user="hello"} 315153582896 (293.51 GB)
telemt_user_unique_ips_current{user="hello"} 299
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 29435.0 (8h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105536
telemt_connections_bad_total 6949
telemt_handshake_timeouts_total 732
telemt_upstream_connect_attempt_total 14259
telemt_upstream_connect_success_total 14139
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 14259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6473
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 24062
telemt_me_reconnect_success_total 12487
telemt_me_reader_eof_total 13223
telemt_me_idle_close_by_peer_total 13223
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 27755
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91945
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 142
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 101
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 12997
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 12464
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 91926
telemt_user_connections_current{user="hello"} 1081
telemt_user_octets_from_client{user="hello"} 4157153525 (3.87 GB)
telemt_user_octets_to_client{user="hello"} 96887561614 (90.23 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 278
telemt_user_unique_ips_recent_window{user="hello"} 135
```