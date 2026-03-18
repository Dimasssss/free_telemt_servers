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

# Server Metrics 2026-03-18 02:33:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 114479.8 (31h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1321697
telemt_connections_bad_total 10146
telemt_handshake_timeouts_total 33163
telemt_upstream_connect_attempt_total 25451
telemt_upstream_connect_success_total 24943
telemt_upstream_connect_fail_total 507
telemt_upstream_connect_attempts_per_request{bucket="1"} 25450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11937
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 507
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 34073
telemt_me_reconnect_success_total 16932
telemt_me_reader_eof_total 18384
telemt_me_idle_close_by_peer_total 18383
telemt_me_route_drop_no_conn_total 571020
telemt_me_route_drop_channel_closed_total 160
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1216619
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7766
telemt_desync_full_logged_total 2298
telemt_desync_suppressed_total 5468
telemt_desync_frames_bucket_total{bucket="1_2"} 2072
telemt_desync_frames_bucket_total{bucket="3_10"} 2960
telemt_desync_frames_bucket_total{bucket="gt_10"} 2734
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 17720
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 16910
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 788
telemt_user_connections_total{user="hello"} 1210831
telemt_user_connections_current{user="hello"} 604
telemt_user_octets_from_client{user="hello"} 24625121695 (22.93 GB)
telemt_user_octets_to_client{user="hello"} 427308659471 (397.96 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 114730.8 (31h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1393858
telemt_connections_bad_total 64253
telemt_handshake_timeouts_total 47183
telemt_upstream_connect_attempt_total 468350
telemt_upstream_connect_success_total 466769
telemt_upstream_connect_fail_total 1581
telemt_upstream_connect_attempts_per_request{bucket="1"} 468350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33430
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1581
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 123565
telemt_me_reconnect_success_total 18124
telemt_me_reader_eof_total 20298
telemt_me_idle_close_by_peer_total 20285
telemt_me_route_drop_no_conn_total 359124
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 769710
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3606
telemt_desync_full_logged_total 1234
telemt_desync_suppressed_total 2372
telemt_desync_frames_bucket_total{bucket="1_2"} 711
telemt_desync_frames_bucket_total{bucket="3_10"} 1502
telemt_desync_frames_bucket_total{bucket="gt_10"} 1393
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 19691
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 18106
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1567
telemt_user_connections_total{user="hello"} 1212061
telemt_user_connections_current{user="hello"} 714
telemt_user_octets_from_client{user="hello"} 16351474721 (15.23 GB)
telemt_user_octets_to_client{user="hello"} 425078142858 (395.88 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 275
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 114506.9 (31h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 843579
telemt_connections_bad_total 58777
telemt_handshake_timeouts_total 24644
telemt_upstream_connect_attempt_total 26759
telemt_upstream_connect_success_total 26604
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 26759
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14306
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 41532
telemt_me_reconnect_success_total 20839
telemt_me_reader_eof_total 22678
telemt_me_idle_close_by_peer_total 22671
telemt_me_route_drop_no_conn_total 332674
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 709419
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2234
telemt_desync_full_logged_total 722
telemt_desync_suppressed_total 1512
telemt_desync_frames_bucket_total{bucket="1_2"} 634
telemt_desync_frames_bucket_total{bucket="3_10"} 870
telemt_desync_frames_bucket_total{bucket="gt_10"} 730
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 21765
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 20827
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 926
telemt_user_connections_total{user="hello"} 707537
telemt_user_connections_current{user="hello"} 521
telemt_user_octets_from_client{user="hello"} 44007172500 (40.98 GB)
telemt_user_octets_to_client{user="hello"} 315965024820 (294.27 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 114566.4 (31h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1321130
telemt_connections_bad_total 59731
telemt_handshake_timeouts_total 22112
telemt_upstream_connect_attempt_total 89515
telemt_upstream_connect_success_total 87101
telemt_upstream_connect_fail_total 2414
telemt_upstream_connect_attempts_per_request{bucket="1"} 89515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13965
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 368
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2414
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 37010
telemt_me_reconnect_success_total 16614
telemt_me_reader_eof_total 18302
telemt_me_idle_close_by_peer_total 18300
telemt_me_route_drop_no_conn_total 542638
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1073209
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3983
telemt_desync_full_logged_total 1319
telemt_desync_suppressed_total 2664
telemt_desync_frames_bucket_total{bucket="1_2"} 972
telemt_desync_frames_bucket_total{bucket="3_10"} 1672
telemt_desync_frames_bucket_total{bucket="gt_10"} 1339
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 17565
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 16603
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 951
telemt_user_connections_total{user="hello"} 1136583
telemt_user_connections_current{user="hello"} 582
telemt_user_octets_from_client{user="hello"} 17813564362 (16.59 GB)
telemt_user_octets_to_client{user="hello"} 538809682002 (501.81 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 114538.2 (31h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 879131
telemt_connections_bad_total 100909
telemt_handshake_timeouts_total 6889
telemt_upstream_connect_attempt_total 46321
telemt_upstream_connect_success_total 45689
telemt_upstream_connect_fail_total 632
telemt_upstream_connect_attempts_per_request{bucket="1"} 46321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16751
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 416
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 632
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 58446
telemt_me_reconnect_success_total 23483
telemt_me_reader_eof_total 25461
telemt_me_idle_close_by_peer_total 25458
telemt_me_route_drop_no_conn_total 280879
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 711607
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3237
telemt_desync_full_logged_total 973
telemt_desync_suppressed_total 2264
telemt_desync_frames_bucket_total{bucket="1_2"} 1010
telemt_desync_frames_bucket_total{bucket="3_10"} 1292
telemt_desync_frames_bucket_total{bucket="gt_10"} 935
telemt_pool_swap_total 59
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24950
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 23475
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1467
telemt_user_connections_total{user="hello"} 728166
telemt_user_connections_current{user="hello"} 523
telemt_user_octets_from_client{user="hello"} 13956219476 (13.00 GB)
telemt_user_octets_to_client{user="hello"} 359217972140 (334.55 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 114699.1 (31h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1128637
telemt_connections_bad_total 122412
telemt_handshake_timeouts_total 9896
telemt_upstream_connect_attempt_total 22839
telemt_upstream_connect_success_total 22709
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 22839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11696
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 28282
telemt_me_reconnect_success_total 16993
telemt_me_reader_eof_total 18430
telemt_me_idle_close_by_peer_total 18428
telemt_me_route_drop_no_conn_total 777515
telemt_me_route_drop_channel_closed_total 89
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1102615
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 102
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 17615
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 16979
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 622
telemt_user_connections_total{user="hello"} 925315
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 14941904380 (13.92 GB)
telemt_user_octets_to_client{user="hello"} 404357229416 (376.59 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 62466.3 (17h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 431463
telemt_connections_bad_total 44754
telemt_handshake_timeouts_total 11514
telemt_upstream_connect_attempt_total 23030
telemt_upstream_connect_success_total 22806
telemt_upstream_connect_fail_total 224
telemt_upstream_connect_attempts_per_request{bucket="1"} 23030
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12231
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10479
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 224
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 31137
telemt_me_reconnect_success_total 19529
telemt_me_reader_eof_total 20652
telemt_me_idle_close_by_peer_total 20652
telemt_me_seq_mismatch_total 28
telemt_me_route_drop_no_conn_total 106256
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 312281
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 32
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1367
telemt_desync_full_logged_total 435
telemt_desync_suppressed_total 932
telemt_desync_frames_bucket_total{bucket="1_2"} 227
telemt_desync_frames_bucket_total{bucket="3_10"} 619
telemt_desync_frames_bucket_total{bucket="gt_10"} 521
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20109
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 19491
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 580
telemt_user_connections_total{user="hello"} 312217
telemt_user_connections_current{user="hello"} 351
telemt_user_octets_from_client{user="hello"} 22631572269 (21.08 GB)
telemt_user_octets_to_client{user="hello"} 261128640954 (243.19 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 35
```