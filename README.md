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

# Server Metrics 2026-03-18 00:41:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 107757.6 (29h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1264881
telemt_connections_bad_total 9575
telemt_handshake_timeouts_total 32453
telemt_upstream_connect_attempt_total 24102
telemt_upstream_connect_success_total 23603
telemt_upstream_connect_fail_total 499
telemt_upstream_connect_attempts_per_request{bucket="1"} 24102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 499
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 33080
telemt_me_reconnect_success_total 15944
telemt_me_reader_eof_total 17312
telemt_me_idle_close_by_peer_total 17311
telemt_me_route_drop_no_conn_total 556956
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1162685
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7529
telemt_desync_full_logged_total 2205
telemt_desync_suppressed_total 5324
telemt_desync_frames_bucket_total{bucket="1_2"} 2015
telemt_desync_frames_bucket_total{bucket="3_10"} 2853
telemt_desync_frames_bucket_total{bucket="gt_10"} 2661
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 16715
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 15922
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 771
telemt_user_connections_total{user="hello"} 1156897
telemt_user_connections_current{user="hello"} 574
telemt_user_octets_from_client{user="hello"} 22739899143 (21.18 GB)
telemt_user_octets_to_client{user="hello"} 415521072255 (386.98 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 108008.9 (30h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1343512
telemt_connections_bad_total 62102
telemt_handshake_timeouts_total 46083
telemt_upstream_connect_attempt_total 466630
telemt_upstream_connect_success_total 465084
telemt_upstream_connect_fail_total 1546
telemt_upstream_connect_attempts_per_request{bucket="1"} 466630
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389227
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32507
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43348
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1546
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 122222
telemt_me_reconnect_success_total 16793
telemt_me_reader_eof_total 18902
telemt_me_idle_close_by_peer_total 18892
telemt_me_route_drop_no_conn_total 347187
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 724611
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3301
telemt_desync_full_logged_total 1100
telemt_desync_suppressed_total 2201
telemt_desync_frames_bucket_total{bucket="1_2"} 642
telemt_desync_frames_bucket_total{bucket="3_10"} 1359
telemt_desync_frames_bucket_total{bucket="gt_10"} 1300
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 18338
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 16775
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1545
telemt_user_connections_total{user="hello"} 1166960
telemt_user_connections_current{user="hello"} 624
telemt_user_octets_from_client{user="hello"} 15849275165 (14.76 GB)
telemt_user_octets_to_client{user="hello"} 399387686606 (371.96 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 107784.8 (29h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 795374
telemt_connections_bad_total 51931
telemt_handshake_timeouts_total 24064
telemt_upstream_connect_attempt_total 25319
telemt_upstream_connect_success_total 25174
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 25319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13542
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 40443
telemt_me_reconnect_success_total 19759
telemt_me_reader_eof_total 21523
telemt_me_idle_close_by_peer_total 21516
telemt_me_route_drop_no_conn_total 321452
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 675792
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2164
telemt_desync_full_logged_total 703
telemt_desync_suppressed_total 1461
telemt_desync_frames_bucket_total{bucket="1_2"} 614
telemt_desync_frames_bucket_total{bucket="3_10"} 835
telemt_desync_frames_bucket_total{bucket="gt_10"} 715
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 20674
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 19747
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 915
telemt_user_connections_total{user="hello"} 673966
telemt_user_connections_current{user="hello"} 412
telemt_user_octets_from_client{user="hello"} 33651397008 (31.34 GB)
telemt_user_octets_to_client{user="hello"} 298179729120 (277.70 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 107844.5 (29h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1282099
telemt_connections_bad_total 53091
telemt_handshake_timeouts_total 21828
telemt_upstream_connect_attempt_total 86427
telemt_upstream_connect_success_total 85007
telemt_upstream_connect_fail_total 1420
telemt_upstream_connect_attempts_per_request{bucket="1"} 86427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13201
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1420
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 35985
telemt_me_reconnect_success_total 15624
telemt_me_reader_eof_total 17237
telemt_me_idle_close_by_peer_total 17235
telemt_me_route_drop_no_conn_total 524669
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1043688
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3929
telemt_desync_full_logged_total 1302
telemt_desync_suppressed_total 2627
telemt_desync_frames_bucket_total{bucket="1_2"} 960
telemt_desync_frames_bucket_total{bucket="3_10"} 1653
telemt_desync_frames_bucket_total{bucket="gt_10"} 1316
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 16552
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 15614
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 928
telemt_user_connections_total{user="hello"} 1106809
telemt_user_connections_current{user="hello"} 575
telemt_user_octets_from_client{user="hello"} 17372520523 (16.18 GB)
telemt_user_octets_to_client{user="hello"} 517789551230 (482.23 GB)
telemt_user_msgs_from_client{user="hello"} 738254
telemt_user_msgs_to_client{user="hello"} 5205558
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 107816.3 (29h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 840265
telemt_connections_bad_total 99175
telemt_handshake_timeouts_total 6767
telemt_upstream_connect_attempt_total 44478
telemt_upstream_connect_success_total 43865
telemt_upstream_connect_fail_total 613
telemt_upstream_connect_attempts_per_request{bucket="1"} 44478
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15772
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 412
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 613
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 56968
telemt_me_reconnect_success_total 22010
telemt_me_reader_eof_total 23899
telemt_me_idle_close_by_peer_total 23897
telemt_me_route_drop_no_conn_total 266146
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 675981
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3179
telemt_desync_full_logged_total 943
telemt_desync_suppressed_total 2236
telemt_desync_frames_bucket_total{bucket="1_2"} 1005
telemt_desync_frames_bucket_total{bucket="3_10"} 1272
telemt_desync_frames_bucket_total{bucket="gt_10"} 902
telemt_pool_swap_total 53
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23459
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 22002
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1449
telemt_user_connections_total{user="hello"} 692589
telemt_user_connections_current{user="hello"} 449
telemt_user_octets_from_client{user="hello"} 13580327132 (12.65 GB)
telemt_user_octets_to_client{user="hello"} 347702788976 (323.82 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 107977.3 (29h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1080088
telemt_connections_bad_total 104454
telemt_handshake_timeouts_total 9638
telemt_upstream_connect_attempt_total 21446
telemt_upstream_connect_success_total 21327
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 21446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11029
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 27244
telemt_me_reconnect_success_total 15962
telemt_me_reader_eof_total 17320
telemt_me_idle_close_by_peer_total 17318
telemt_me_route_drop_no_conn_total 726460
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1044622
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
telemt_pool_swap_total 94
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 16571
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 15948
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 609
telemt_user_connections_total{user="hello"} 896583
telemt_user_connections_current{user="hello"} 413
telemt_user_octets_from_client{user="hello"} 14453349856 (13.46 GB)
telemt_user_octets_to_client{user="hello"} 380264286040 (354.15 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 55744.5 (15h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 394145
telemt_connections_bad_total 44682
telemt_handshake_timeouts_total 10850
telemt_upstream_connect_attempt_total 20891
telemt_upstream_connect_success_total 20702
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 20891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 29375
telemt_me_reconnect_success_total 17776
telemt_me_reader_eof_total 18803
telemt_me_idle_close_by_peer_total 18803
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 98606
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 290869
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1102
telemt_desync_full_logged_total 347
telemt_desync_suppressed_total 755
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 474
telemt_desync_frames_bucket_total{bucket="gt_10"} 414
telemt_pool_swap_total 35
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18340
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 17745
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 564
telemt_user_connections_total{user="hello"} 290810
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 22227320261 (20.70 GB)
telemt_user_octets_to_client{user="hello"} 241479047958 (224.89 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 20
```