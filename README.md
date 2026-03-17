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

# Server Metrics 2026-03-17 22:39:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 100425.3 (27h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1214065
telemt_connections_bad_total 8787
telemt_handshake_timeouts_total 32204
telemt_upstream_connect_attempt_total 22691
telemt_upstream_connect_success_total 22197
telemt_upstream_connect_fail_total 494
telemt_upstream_connect_attempts_per_request{bucket="1"} 22691
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10550
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 494
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 32018
telemt_me_reconnect_success_total 14886
telemt_me_reader_eof_total 16175
telemt_me_idle_close_by_peer_total 16174
telemt_me_route_drop_no_conn_total 540091
telemt_me_route_drop_channel_closed_total 156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1114090
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7332
telemt_desync_full_logged_total 2126
telemt_desync_suppressed_total 5206
telemt_desync_frames_bucket_total{bucket="1_2"} 1961
telemt_desync_frames_bucket_total{bucket="3_10"} 2771
telemt_desync_frames_bucket_total{bucket="gt_10"} 2600
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 15640
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 14864
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 754
telemt_user_connections_total{user="hello"} 1108315
telemt_user_connections_current{user="hello"} 513
telemt_user_octets_from_client{user="hello"} 20573975507 (19.16 GB)
telemt_user_octets_to_client{user="hello"} 399182433535 (371.77 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 100676.6 (27h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1283232
telemt_connections_bad_total 60358
telemt_handshake_timeouts_total 45010
telemt_upstream_connect_attempt_total 458135
telemt_upstream_connect_success_total 457233
telemt_upstream_connect_fail_total 902
telemt_upstream_connect_attempts_per_request{bucket="1"} 458135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 383067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30873
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 902
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 58372
telemt_me_reconnect_success_total 15216
telemt_me_reader_eof_total 17220
telemt_me_idle_close_by_peer_total 17220
telemt_me_route_drop_no_conn_total 333048
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 675954
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3016
telemt_desync_full_logged_total 990
telemt_desync_suppressed_total 2026
telemt_desync_frames_bucket_total{bucket="1_2"} 573
telemt_desync_frames_bucket_total{bucket="3_10"} 1239
telemt_desync_frames_bucket_total{bucket="gt_10"} 1204
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 16751
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 15200
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1535
telemt_user_connections_total{user="hello"} 1112386
telemt_user_connections_current{user="hello"} 866
telemt_user_octets_from_client{user="hello"} 15257663650 (14.21 GB)
telemt_user_octets_to_client{user="hello"} 378440631142 (352.45 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 310
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 100452.7 (27h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 744201
telemt_connections_bad_total 46077
telemt_handshake_timeouts_total 23506
telemt_upstream_connect_attempt_total 23783
telemt_upstream_connect_success_total 23644
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 23783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12716
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 39259
telemt_me_reconnect_success_total 18579
telemt_me_reader_eof_total 20258
telemt_me_idle_close_by_peer_total 20251
telemt_me_route_drop_no_conn_total 308095
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 636428
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2096
telemt_desync_full_logged_total 666
telemt_desync_suppressed_total 1430
telemt_desync_frames_bucket_total{bucket="1_2"} 587
telemt_desync_frames_bucket_total{bucket="3_10"} 813
telemt_desync_frames_bucket_total{bucket="gt_10"} 696
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 19478
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 18567
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 899
telemt_user_connections_total{user="hello"} 634689
telemt_user_connections_current{user="hello"} 627
telemt_user_octets_from_client{user="hello"} 31058596208 (28.93 GB)
telemt_user_octets_to_client{user="hello"} 276421052512 (257.44 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 100512.2 (27h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1237743
telemt_connections_bad_total 43850
telemt_handshake_timeouts_total 21602
telemt_upstream_connect_attempt_total 83398
telemt_upstream_connect_success_total 82966
telemt_upstream_connect_fail_total 432
telemt_upstream_connect_attempts_per_request{bucket="1"} 83398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12433
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 346
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 432
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 34896
telemt_me_reconnect_success_total 14574
telemt_me_reader_eof_total 16063
telemt_me_idle_close_by_peer_total 16061
telemt_me_route_drop_no_conn_total 511258
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1011853
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3770
telemt_desync_full_logged_total 1233
telemt_desync_suppressed_total 2537
telemt_desync_frames_bucket_total{bucket="1_2"} 921
telemt_desync_frames_bucket_total{bucket="3_10"} 1589
telemt_desync_frames_bucket_total{bucket="gt_10"} 1260
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 15477
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 14565
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 903
telemt_user_connections_total{user="hello"} 1074343
telemt_user_connections_current{user="hello"} 713
telemt_user_octets_from_client{user="hello"} 16834112743 (15.68 GB)
telemt_user_octets_to_client{user="hello"} 475707088641 (443.04 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 100483.9 (27h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 795823
telemt_connections_bad_total 94949
telemt_handshake_timeouts_total 6436
telemt_upstream_connect_attempt_total 42329
telemt_upstream_connect_success_total 41758
telemt_upstream_connect_fail_total 571
telemt_upstream_connect_attempts_per_request{bucket="1"} 42329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14686
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 402
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 571
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 55205
telemt_me_reconnect_success_total 20252
telemt_me_reader_eof_total 22081
telemt_me_idle_close_by_peer_total 22079
telemt_me_route_drop_no_conn_total 251732
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 637155
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2913
telemt_desync_full_logged_total 861
telemt_desync_suppressed_total 2052
telemt_desync_frames_bucket_total{bucket="1_2"} 940
telemt_desync_frames_bucket_total{bucket="3_10"} 1167
telemt_desync_frames_bucket_total{bucket="gt_10"} 806
telemt_pool_swap_total 50
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21687
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 20244
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1435
telemt_user_connections_total{user="hello"} 653765
telemt_user_connections_current{user="hello"} 691
telemt_user_octets_from_client{user="hello"} 12526339444 (11.67 GB)
telemt_user_octets_to_client{user="hello"} 325022035820 (302.70 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 100644.9 (27h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1026510
telemt_connections_bad_total 84873
telemt_handshake_timeouts_total 9516
telemt_upstream_connect_attempt_total 19867
telemt_upstream_connect_success_total 19754
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 19867
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10202
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 26018
telemt_me_reconnect_success_total 14739
telemt_me_reader_eof_total 16006
telemt_me_idle_close_by_peer_total 16004
telemt_me_route_drop_no_conn_total 693756
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1004710
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2082
telemt_desync_full_logged_total 725
telemt_desync_suppressed_total 1357
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 786
telemt_desync_frames_bucket_total{bucket="gt_10"} 835
telemt_pool_swap_total 86
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 15335
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 14725
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 596
telemt_user_connections_total{user="hello"} 867738
telemt_user_connections_current{user="hello"} 512
telemt_user_octets_from_client{user="hello"} 13406268824 (12.49 GB)
telemt_user_octets_to_client{user="hello"} 369131081804 (343.78 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 48412.3 (13h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 359995
telemt_connections_bad_total 44424
telemt_handshake_timeouts_total 10559
telemt_upstream_connect_attempt_total 18704
telemt_upstream_connect_success_total 18529
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 18704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9901
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8535
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 27546
telemt_me_reconnect_success_total 15951
telemt_me_reader_eof_total 16860
telemt_me_idle_close_by_peer_total 16860
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 89969
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 272480
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 938
telemt_desync_full_logged_total 288
telemt_desync_suppressed_total 650
telemt_desync_frames_bucket_total{bucket="1_2"} 212
telemt_desync_frames_bucket_total{bucket="3_10"} 382
telemt_desync_frames_bucket_total{bucket="gt_10"} 344
telemt_pool_swap_total 27
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 16500
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 15922
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 549
telemt_user_connections_total{user="hello"} 272418
telemt_user_connections_current{user="hello"} 370
telemt_user_octets_from_client{user="hello"} 21335054281 (19.87 GB)
telemt_user_octets_to_client{user="hello"} 224556071626 (209.13 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 37
```