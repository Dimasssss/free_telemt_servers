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

# Server Metrics 2026-03-18 06:42:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 129445.7 (35h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1642519
telemt_connections_bad_total 11543
telemt_handshake_timeouts_total 36611
telemt_upstream_connect_attempt_total 28063
telemt_upstream_connect_success_total 27542
telemt_upstream_connect_fail_total 521
telemt_upstream_connect_attempts_per_request{bucket="1"} 28063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13252
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 521
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 279
telemt_me_reconnect_attempts_total 35979
telemt_me_reconnect_success_total 18824
telemt_me_reader_eof_total 20397
telemt_me_idle_close_by_peer_total 20396
telemt_me_route_drop_no_conn_total 635811
telemt_me_route_drop_channel_closed_total 180
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1390499
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8422
telemt_desync_full_logged_total 2542
telemt_desync_suppressed_total 5880
telemt_desync_frames_bucket_total{bucket="1_2"} 2194
telemt_desync_frames_bucket_total{bucket="3_10"} 3247
telemt_desync_frames_bucket_total{bucket="gt_10"} 2981
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 19644
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 18802
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 820
telemt_user_connections_total{user="hello"} 1384743
telemt_user_connections_current{user="hello"} 1156
telemt_user_octets_from_client{user="hello"} 32571896143 (30.33 GB)
telemt_user_octets_to_client{user="hello"} 496421727523 (462.33 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 429
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 129697.3 (36h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1744757
telemt_connections_bad_total 86851
telemt_handshake_timeouts_total 55828
telemt_upstream_connect_attempt_total 471531
telemt_upstream_connect_success_total 469891
telemt_upstream_connect_fail_total 1640
telemt_upstream_connect_attempts_per_request{bucket="1"} 471531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35075
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1640
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 127252
telemt_me_reconnect_success_total 20518
telemt_me_reader_eof_total 22831
telemt_me_idle_close_by_peer_total 22818
telemt_me_route_drop_no_conn_total 469241
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1077691
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4991
telemt_desync_full_logged_total 1732
telemt_desync_suppressed_total 3259
telemt_desync_frames_bucket_total{bucket="1_2"} 948
telemt_desync_frames_bucket_total{bucket="3_10"} 2029
telemt_desync_frames_bucket_total{bucket="gt_10"} 2014
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 22152
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 20500
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1634
telemt_user_connections_total{user="hello"} 1519977
telemt_user_connections_current{user="hello"} 2226
telemt_user_octets_from_client{user="hello"} 23153973521 (21.56 GB)
telemt_user_octets_to_client{user="hello"} 594663248058 (553.82 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 727
telemt_user_unique_ips_recent_window{user="hello"} 306
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 129473.2 (35h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1239170
telemt_connections_bad_total 81256
telemt_handshake_timeouts_total 31420
telemt_upstream_connect_attempt_total 29264
telemt_upstream_connect_success_total 29099
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 29264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15623
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_keepalive_timeout_total 141
telemt_me_reconnect_attempts_total 43335
telemt_me_reconnect_success_total 22627
telemt_me_reader_eof_total 24587
telemt_me_idle_close_by_peer_total 24580
telemt_me_route_drop_no_conn_total 415181
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 931923
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3212
telemt_desync_full_logged_total 1037
telemt_desync_suppressed_total 2175
telemt_desync_frames_bucket_total{bucket="1_2"} 848
telemt_desync_frames_bucket_total{bucket="3_10"} 1242
telemt_desync_frames_bucket_total{bucket="gt_10"} 1122
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 23583
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 22615
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 956
telemt_user_connections_total{user="hello"} 929992
telemt_user_connections_current{user="hello"} 1648
telemt_user_octets_from_client{user="hello"} 47730914636 (44.45 GB)
telemt_user_octets_to_client{user="hello"} 454868446824 (423.63 GB)
telemt_user_unique_ips_current{user="hello"} 499
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 129532.7 (35h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1636005
telemt_connections_bad_total 83478
telemt_handshake_timeouts_total 28928
telemt_upstream_connect_attempt_total 92353
telemt_upstream_connect_success_total 89900
telemt_upstream_connect_fail_total 2453
telemt_upstream_connect_attempts_per_request{bucket="1"} 92353
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15346
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 383
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2453
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 39130
telemt_me_reconnect_success_total 18707
telemt_me_reader_eof_total 20507
telemt_me_idle_close_by_peer_total 20504
telemt_me_route_drop_no_conn_total 652608
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1341545
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5251
telemt_desync_full_logged_total 1682
telemt_desync_suppressed_total 3569
telemt_desync_frames_bucket_total{bucket="1_2"} 1237
telemt_desync_frames_bucket_total{bucket="3_10"} 2169
telemt_desync_frames_bucket_total{bucket="gt_10"} 1845
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 19690
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 18687
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 983
telemt_user_connections_total{user="hello"} 1404794
telemt_user_connections_current{user="hello"} 2095
telemt_user_octets_from_client{user="hello"} 23581963926 (21.96 GB)
telemt_user_octets_to_client{user="hello"} 676970141770 (630.48 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 597
telemt_user_unique_ips_recent_window{user="hello"} 239
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 129504.5 (35h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1172154
telemt_connections_bad_total 107080
telemt_handshake_timeouts_total 12524
telemt_upstream_connect_attempt_total 49448
telemt_upstream_connect_success_total 48767
telemt_upstream_connect_fail_total 681
telemt_upstream_connect_attempts_per_request{bucket="1"} 49448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18315
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 428
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 681
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 60833
telemt_me_reconnect_success_total 25860
telemt_me_reader_eof_total 27943
telemt_me_idle_close_by_peer_total 27940
telemt_me_route_drop_no_conn_total 378454
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 965990
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4162
telemt_desync_full_logged_total 1284
telemt_desync_suppressed_total 2878
telemt_desync_frames_bucket_total{bucket="1_2"} 1140
telemt_desync_frames_bucket_total{bucket="3_10"} 1604
telemt_desync_frames_bucket_total{bucket="gt_10"} 1418
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 27352
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 25852
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1492
telemt_user_connections_total{user="hello"} 982403
telemt_user_connections_current{user="hello"} 1699
telemt_user_octets_from_client{user="hello"} 18282025992 (17.03 GB)
telemt_user_octets_to_client{user="hello"} 497007058900 (462.87 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 579
telemt_user_unique_ips_recent_window{user="hello"} 253
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 129665.9 (36h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1258374
telemt_connections_bad_total 132366
telemt_handshake_timeouts_total 10795
telemt_upstream_connect_attempt_total 25678
telemt_upstream_connect_success_total 25525
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 25678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13124
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_keepalive_timeout_total 152
telemt_me_reconnect_attempts_total 30380
telemt_me_reconnect_success_total 19082
telemt_me_reader_eof_total 20668
telemt_me_idle_close_by_peer_total 20666
telemt_me_route_drop_no_conn_total 843006
telemt_me_route_drop_channel_closed_total 92
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1229981
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2381
telemt_desync_full_logged_total 840
telemt_desync_suppressed_total 1541
telemt_desync_frames_bucket_total{bucket="1_2"} 531
telemt_desync_frames_bucket_total{bucket="3_10"} 914
telemt_desync_frames_bucket_total{bucket="gt_10"} 936
telemt_pool_swap_total 118
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 19727
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 19068
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 645
telemt_user_connections_total{user="hello"} 1038642
telemt_user_connections_current{user="hello"} 854
telemt_user_octets_from_client{user="hello"} 16362148528 (15.24 GB)
telemt_user_octets_to_client{user="hello"} 460561175312 (428.93 GB)
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 77433.1 (21h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 649674
telemt_connections_bad_total 57848
telemt_handshake_timeouts_total 14582
telemt_upstream_connect_attempt_total 26246
telemt_upstream_connect_success_total 25970
telemt_upstream_connect_fail_total 275
telemt_upstream_connect_attempts_per_request{bucket="1"} 26245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12002
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 275
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 33609
telemt_me_reconnect_success_total 21992
telemt_me_reader_eof_total 23240
telemt_me_idle_close_by_peer_total 23240
telemt_me_seq_mismatch_total 35
telemt_me_route_drop_no_conn_total 168929
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 483962
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 720
telemt_desync_suppressed_total 1386
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 925
telemt_desync_frames_bucket_total{bucket="gt_10"} 837
telemt_pool_swap_total 55
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22589
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 21947
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 597
telemt_user_connections_total{user="hello"} 483699
telemt_user_connections_current{user="hello"} 1508
telemt_user_octets_from_client{user="hello"} 27553133277 (25.66 GB)
telemt_user_octets_to_client{user="hello"} 368644950158 (343.33 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 441
telemt_user_unique_ips_recent_window{user="hello"} 219
```