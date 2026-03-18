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

# Server Metrics 2026-03-18 17:41:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 8167.8 (2h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 237006
telemt_connections_bad_total 15557
telemt_handshake_timeouts_total 5997
telemt_upstream_connect_attempt_total 1302
telemt_upstream_connect_success_total 1302
telemt_upstream_connect_attempts_per_request{bucket="1"} 1302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 623
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 856
telemt_me_reconnect_success_total 853
telemt_me_reader_eof_total 875
telemt_me_idle_close_by_peer_total 875
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 110679
telemt_me_route_drop_channel_closed_total 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 200422
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1117
telemt_desync_full_logged_total 339
telemt_desync_suppressed_total 778
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 359
telemt_desync_frames_bucket_total{bucket="gt_10"} 501
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 873
telemt_me_writer_restored_same_endpoint_total 840
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 200334
telemt_user_connections_current{user="hello"} 1368
telemt_user_octets_from_client{user="hello"} 2786916992 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 67809120332 (63.15 GB)
telemt_user_unique_ips_current{user="hello"} 467
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 12995.8 (3h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1338067
telemt_connections_bad_total 80837
telemt_connections_current 3565
telemt_connections_me_current 3565
telemt_handshake_timeouts_total 26200
telemt_upstream_connect_attempt_total 2283
telemt_upstream_connect_success_total 2271
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1027
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 1594
telemt_me_reconnect_success_total 1580
telemt_me_reader_eof_total 1545
telemt_me_idle_close_by_peer_total 1544
telemt_me_route_drop_no_conn_total 1442866
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1164543
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3382
telemt_desync_full_logged_total 1079
telemt_desync_suppressed_total 2303
telemt_desync_frames_bucket_total{bucket="1_2"} 639
telemt_desync_frames_bucket_total{bucket="3_10"} 1335
telemt_desync_frames_bucket_total{bucket="gt_10"} 1408
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1516
telemt_me_writer_restored_same_endpoint_total 1578
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1159853
telemt_user_connections_current{user="hello"} 3565
telemt_user_octets_from_client{user="hello"} 15043322184 (14.01 GB)
telemt_user_octets_to_client{user="hello"} 332076239016 (309.27 GB)
telemt_user_unique_ips_current{user="hello"} 1137
telemt_user_unique_ips_recent_window{user="hello"} 465
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 12923.8 (3h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 920249
telemt_connections_bad_total 73084
telemt_connections_current 3425
telemt_connections_me_current 3425
telemt_handshake_timeouts_total 20615
telemt_upstream_connect_attempt_total 1831
telemt_upstream_connect_success_total 1820
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1830
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 849
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1143
telemt_me_reconnect_success_total 1130
telemt_me_reader_eof_total 1197
telemt_me_idle_close_by_peer_total 1197
telemt_me_route_drop_no_conn_total 420323
telemt_me_route_drop_channel_closed_total 38
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 761905
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3114
telemt_desync_full_logged_total 951
telemt_desync_suppressed_total 2163
telemt_desync_frames_bucket_total{bucket="1_2"} 757
telemt_desync_frames_bucket_total{bucket="3_10"} 1160
telemt_desync_frames_bucket_total{bucket="gt_10"} 1197
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1166
telemt_me_writer_restored_same_endpoint_total 1113
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 761543
telemt_user_connections_current{user="hello"} 3425
telemt_user_octets_from_client{user="hello"} 18096175836 (16.85 GB)
telemt_user_octets_to_client{user="hello"} 324251904864 (301.98 GB)
telemt_user_unique_ips_current{user="hello"} 1018
telemt_user_unique_ips_recent_window{user="hello"} 434
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 13638.3 (3h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1358409
telemt_connections_bad_total 28565
telemt_connections_current 2830
telemt_connections_me_current 2830
telemt_handshake_timeouts_total 15962
telemt_upstream_connect_attempt_total 2116
telemt_upstream_connect_success_total 2100
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 986
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1375
telemt_me_reconnect_success_total 1356
telemt_me_reader_eof_total 1386
telemt_me_idle_close_by_peer_total 1385
telemt_me_route_drop_no_conn_total 2289549
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1215810
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4515
telemt_desync_full_logged_total 1147
telemt_desync_suppressed_total 3368
telemt_desync_frames_bucket_total{bucket="1_2"} 1051
telemt_desync_frames_bucket_total{bucket="3_10"} 2065
telemt_desync_frames_bucket_total{bucket="gt_10"} 1399
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1355
telemt_me_writer_restored_same_endpoint_total 1345
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 1215728
telemt_user_connections_current{user="hello"} 2830
telemt_user_octets_from_client{user="hello"} 11285634328 (10.51 GB)
telemt_user_octets_to_client{user="hello"} 204633325440 (190.58 GB)
telemt_user_unique_ips_current{user="hello"} 883
telemt_user_unique_ips_recent_window{user="hello"} 374
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 8153.1 (2h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 613065
telemt_connections_bad_total 111102
telemt_handshake_timeouts_total 5886
telemt_upstream_connect_attempt_total 1468
telemt_upstream_connect_success_total 1421
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 1468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 667
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 1993
telemt_me_reconnect_success_total 992
telemt_me_reader_eof_total 1024
telemt_me_idle_close_by_peer_total 1024
telemt_me_route_drop_no_conn_total 245417
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 450407
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1715
telemt_desync_full_logged_total 575
telemt_desync_suppressed_total 1140
telemt_desync_frames_bucket_total{bucket="1_2"} 315
telemt_desync_frames_bucket_total{bucket="3_10"} 576
telemt_desync_frames_bucket_total{bucket="gt_10"} 824
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1034
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 966
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 449918
telemt_user_connections_current{user="hello"} 3295
telemt_user_octets_from_client{user="hello"} 7178592816 (6.69 GB)
telemt_user_octets_to_client{user="hello"} 190689009024 (177.59 GB)
telemt_user_unique_ips_current{user="hello"} 1096
telemt_user_unique_ips_recent_window{user="hello"} 460
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 13087.6 (3h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 241656
telemt_connections_bad_total 9170
telemt_connections_current 858
telemt_connections_me_current 858
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 2608
telemt_upstream_connect_attempt_total 6383
telemt_upstream_connect_success_total 6370
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 6383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2915
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 43
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 331319
telemt_me_reconnect_success_total 1853
telemt_me_reader_eof_total 1836
telemt_me_idle_close_by_peer_total 1836
telemt_me_route_drop_no_conn_total 158169
telemt_me_route_drop_channel_closed_total 62
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 214137
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 424
telemt_desync_full_logged_total 153
telemt_desync_suppressed_total 271
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 176
telemt_desync_frames_bucket_total{bucket="gt_10"} 170
telemt_pool_swap_total 10
telemt_pool_stale_pick_total 139
telemt_me_writer_removed_unexpected_total 1795
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1842
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 217854
telemt_user_connections_current{user="hello"} 858
telemt_user_octets_from_client{user="hello"} 3163399781 (2.95 GB)
telemt_user_octets_to_client{user="hello"} 44484074217 (41.43 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 12157.7 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 739605
telemt_connections_bad_total 53620
telemt_connections_current 2912
telemt_connections_me_current 2912
telemt_handshake_timeouts_total 13811
telemt_upstream_connect_attempt_total 2147
telemt_upstream_connect_success_total 2146
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 956
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17011
telemt_me_reconnect_success_total 1497
telemt_me_reader_eof_total 1481
telemt_me_idle_close_by_peer_total 1481
telemt_me_route_drop_no_conn_total 405875
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 618999
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2395
telemt_desync_full_logged_total 815
telemt_desync_suppressed_total 1580
telemt_desync_frames_bucket_total{bucket="1_2"} 608
telemt_desync_frames_bucket_total{bucket="3_10"} 845
telemt_desync_frames_bucket_total{bucket="gt_10"} 942
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1460
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1436
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 618022
telemt_user_connections_current{user="hello"} 2912
telemt_user_octets_from_client{user="hello"} 11718731932 (10.91 GB)
telemt_user_octets_to_client{user="hello"} 305755634732 (284.76 GB)
telemt_user_unique_ips_current{user="hello"} 916
telemt_user_unique_ips_recent_window{user="hello"} 372
```