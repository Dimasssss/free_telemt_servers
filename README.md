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

# Server Metrics 2026-03-17 17:48:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 82982.6 (23h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1002272
telemt_connections_bad_total 6647
telemt_handshake_timeouts_total 27909
telemt_upstream_connect_attempt_total 19596
telemt_upstream_connect_success_total 19116
telemt_upstream_connect_fail_total 480
telemt_upstream_connect_attempts_per_request{bucket="1"} 19596
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8981
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 480
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 173
telemt_me_reconnect_attempts_total 29756
telemt_me_reconnect_success_total 12639
telemt_me_reader_eof_total 13773
telemt_me_idle_close_by_peer_total 13772
telemt_me_route_drop_no_conn_total 458188
telemt_me_route_drop_channel_closed_total 125
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 917120
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6102
telemt_desync_full_logged_total 1728
telemt_desync_suppressed_total 4374
telemt_desync_frames_bucket_total{bucket="1_2"} 1681
telemt_desync_frames_bucket_total{bucket="3_10"} 2348
telemt_desync_frames_bucket_total{bucket="gt_10"} 2073
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 13352
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 12617
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 713
telemt_user_connections_total{user="hello"} 911374
telemt_user_connections_current{user="hello"} 1084
telemt_user_octets_from_client{user="hello"} 13964814331 (13.01 GB)
telemt_user_octets_to_client{user="hello"} 312818904699 (291.34 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 371
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 83234.7 (23h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 879884
telemt_connections_bad_total 51445
telemt_handshake_timeouts_total 32079
telemt_upstream_connect_attempt_total 355236
telemt_upstream_connect_success_total 354455
telemt_upstream_connect_fail_total 776
telemt_upstream_connect_attempts_per_request{bucket="1"} 355231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 294744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25826
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33883
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 776
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 52586
telemt_me_reconnect_success_total 13565
telemt_me_reader_eof_total 15337
telemt_me_idle_close_by_peer_total 15337
telemt_me_route_drop_no_conn_total 236689
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 417225
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1561
telemt_desync_full_logged_total 496
telemt_desync_suppressed_total 1065
telemt_desync_frames_bucket_total{bucket="1_2"} 355
telemt_desync_frames_bucket_total{bucket="3_10"} 681
telemt_desync_frames_bucket_total{bucket="gt_10"} 525
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14947
telemt_me_refill_failed_total 1215
telemt_me_writer_restored_same_endpoint_total 13549
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1382
telemt_user_connections_total{user="hello"} 753830
telemt_user_connections_current{user="hello"} 1871
telemt_user_octets_from_client{user="hello"} 10140014974 (9.44 GB)
telemt_user_octets_to_client{user="hello"} 203253447051 (189.29 GB)
telemt_user_msgs_from_client{user="hello"} 5727813
telemt_user_msgs_to_client{user="hello"} 24048720
telemt_user_unique_ips_current{user="hello"} 440
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 83010.1 (23h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 451473
telemt_connections_bad_total 14805
telemt_handshake_timeouts_total 20725
telemt_upstream_connect_attempt_total 20739
telemt_upstream_connect_success_total 20621
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 20739
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11164
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 37057
telemt_me_reconnect_success_total 16389
telemt_me_reader_eof_total 17931
telemt_me_idle_close_by_peer_total 17924
telemt_me_route_drop_no_conn_total 213610
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 393722
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1113
telemt_desync_full_logged_total 337
telemt_desync_suppressed_total 776
telemt_desync_frames_bucket_total{bucket="1_2"} 366
telemt_desync_frames_bucket_total{bucket="3_10"} 485
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 17255
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16377
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 866
telemt_user_connections_total{user="hello"} 391886
telemt_user_connections_current{user="hello"} 1324
telemt_user_octets_from_client{user="hello"} 25423749344 (23.68 GB)
telemt_user_octets_to_client{user="hello"} 140472411080 (130.83 GB)
telemt_user_unique_ips_current{user="hello"} 371
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 83069.3 (23h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 924125
telemt_connections_bad_total 21401
telemt_handshake_timeouts_total 17973
telemt_upstream_connect_attempt_total 80503
telemt_upstream_connect_success_total 80106
telemt_upstream_connect_fail_total 397
telemt_upstream_connect_attempts_per_request{bucket="1"} 80503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10937
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 331
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 397
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 32848
telemt_me_reconnect_success_total 12547
telemt_me_reader_eof_total 13860
telemt_me_idle_close_by_peer_total 13859
telemt_me_route_drop_no_conn_total 391688
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 740334
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2377
telemt_desync_full_logged_total 763
telemt_desync_suppressed_total 1614
telemt_desync_frames_bucket_total{bucket="1_2"} 576
telemt_desync_frames_bucket_total{bucket="3_10"} 1057
telemt_desync_frames_bucket_total{bucket="gt_10"} 744
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 13409
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12538
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 862
telemt_user_connections_total{user="hello"} 803433
telemt_user_connections_current{user="hello"} 1712
telemt_user_octets_from_client{user="hello"} 9786439167 (9.11 GB)
telemt_user_octets_to_client{user="hello"} 268189843305 (249.77 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 457
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 83041.2 (23h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 498565
telemt_connections_bad_total 71856
telemt_handshake_timeouts_total 4515
telemt_upstream_connect_attempt_total 38898
telemt_upstream_connect_success_total 38393
telemt_upstream_connect_fail_total 505
telemt_upstream_connect_attempts_per_request{bucket="1"} 38898
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25148
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12887
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 358
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 505
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 50195
telemt_me_reconnect_success_total 17716
telemt_me_reader_eof_total 19345
telemt_me_idle_close_by_peer_total 19343
telemt_me_route_drop_no_conn_total 146424
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 378015
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1687
telemt_desync_full_logged_total 419
telemt_desync_suppressed_total 1268
telemt_desync_frames_bucket_total{bucket="1_2"} 676
telemt_desync_frames_bucket_total{bucket="3_10"} 668
telemt_desync_frames_bucket_total{bucket="gt_10"} 343
telemt_pool_swap_total 39
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19026
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 17708
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1310
telemt_user_connections_total{user="hello"} 394708
telemt_user_connections_current{user="hello"} 1614
telemt_user_octets_from_client{user="hello"} 6900134604 (6.43 GB)
telemt_user_octets_to_client{user="hello"} 179747727408 (167.40 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 442
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 83203.6 (23h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 845465
telemt_connections_bad_total 60584
telemt_handshake_timeouts_total 8085
telemt_upstream_connect_attempt_total 16708
telemt_upstream_connect_success_total 16616
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 16708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7943
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8596
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 23699
telemt_me_reconnect_success_total 12429
telemt_me_reader_eof_total 13527
telemt_me_idle_close_by_peer_total 13525
telemt_me_route_drop_no_conn_total 626975
telemt_me_route_drop_channel_closed_total 77
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 868747
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1562
telemt_desync_full_logged_total 538
telemt_desync_suppressed_total 1024
telemt_desync_frames_bucket_total{bucket="1_2"} 378
telemt_desync_frames_bucket_total{bucket="3_10"} 605
telemt_desync_frames_bucket_total{bucket="gt_10"} 579
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 12991
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 12415
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 562
telemt_user_connections_total{user="hello"} 731810
telemt_user_connections_current{user="hello"} 847
telemt_user_octets_from_client{user="hello"} 11119918756 (10.36 GB)
telemt_user_octets_to_client{user="hello"} 320464042040 (298.46 GB)
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 30969.5 (8h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145910
telemt_connections_bad_total 17703
telemt_handshake_timeouts_total 4730
telemt_upstream_connect_attempt_total 14555
telemt_upstream_connect_success_total 14429
telemt_upstream_connect_fail_total 126
telemt_upstream_connect_attempts_per_request{bucket="1"} 14555
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6600
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 126
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 24265
telemt_me_reconnect_success_total 12688
telemt_me_reader_eof_total 13431
telemt_me_idle_close_by_peer_total 13431
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 34592
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115394
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 194
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 141
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 13200
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 12665
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 512
telemt_user_connections_total{user="hello"} 115355
telemt_user_connections_current{user="hello"} 1034
telemt_user_octets_from_client{user="hello"} 8032199049 (7.48 GB)
telemt_user_octets_to_client{user="hello"} 113137491226 (105.37 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 256
telemt_user_unique_ips_recent_window{user="hello"} 112
```