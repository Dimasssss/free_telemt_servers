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

# Server Metrics 2026-03-17 16:21:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 77778.1 (21h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 894920
telemt_connections_bad_total 6359
telemt_handshake_timeouts_total 25479
telemt_upstream_connect_attempt_total 18570
telemt_upstream_connect_success_total 18098
telemt_upstream_connect_fail_total 472
telemt_upstream_connect_attempts_per_request{bucket="1"} 18570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8472
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 472
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 169
telemt_me_reconnect_attempts_total 28997
telemt_me_reconnect_success_total 11884
telemt_me_reader_eof_total 12975
telemt_me_idle_close_by_peer_total 12974
telemt_me_route_drop_no_conn_total 412950
telemt_me_route_drop_channel_closed_total 102
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 822124
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5547
telemt_desync_full_logged_total 1538
telemt_desync_suppressed_total 4009
telemt_desync_frames_bucket_total{bucket="1_2"} 1586
telemt_desync_frames_bucket_total{bucket="3_10"} 2154
telemt_desync_frames_bucket_total{bucket="gt_10"} 1807
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 12582
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 11862
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 698
telemt_user_connections_total{user="hello"} 816556
telemt_user_connections_current{user="hello"} 1329
telemt_user_octets_from_client{user="hello"} 12764040599 (11.89 GB)
telemt_user_octets_to_client{user="hello"} 269885182223 (251.35 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 403
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 78029.5 (21h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 604317
telemt_connections_bad_total 32468
telemt_handshake_timeouts_total 28905
telemt_upstream_connect_attempt_total 156028
telemt_upstream_connect_success_total 155439
telemt_upstream_connect_fail_total 589
telemt_upstream_connect_attempts_per_request{bucket="1"} 156028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 127953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15544
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11940
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 589
telemt_me_keepalive_timeout_total 332
telemt_me_reconnect_attempts_total 44296
telemt_me_reconnect_success_total 13533
telemt_me_reader_eof_total 15047
telemt_me_idle_close_by_peer_total 15047
telemt_me_route_drop_no_conn_total 198489
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 378044
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1494
telemt_desync_full_logged_total 469
telemt_desync_suppressed_total 1025
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 651
telemt_desync_frames_bucket_total{bucket="gt_10"} 507
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14657
telemt_me_refill_failed_total 957
telemt_me_writer_restored_same_endpoint_total 13517
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1124
telemt_user_connections_total{user="hello"} 515941
telemt_user_connections_current{user="hello"} 1259
telemt_user_octets_from_client{user="hello"} 5694550238 (5.30 GB)
telemt_user_octets_to_client{user="hello"} 141831926031 (132.09 GB)
telemt_user_msgs_from_client{user="hello"} 2015652
telemt_user_msgs_to_client{user="hello"} 7649204
telemt_user_unique_ips_current{user="hello"} 280
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 77805.8 (21h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300951
telemt_connections_bad_total 7912
telemt_handshake_timeouts_total 19290
telemt_upstream_connect_attempt_total 19957
telemt_upstream_connect_success_total 19851
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 19957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10784
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 35147
telemt_me_reconnect_success_total 15884
telemt_me_reader_eof_total 17345
telemt_me_idle_close_by_peer_total 17342
telemt_me_route_drop_no_conn_total 143349
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 258340
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 829
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 587
telemt_desync_frames_bucket_total{bucket="1_2"} 300
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 157
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 16695
telemt_me_refill_failed_total 599
telemt_me_writer_restored_same_endpoint_total 15873
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 811
telemt_user_connections_total{user="hello"} 258185
telemt_user_connections_current{user="hello"} 723
telemt_user_octets_from_client{user="hello"} 20200384944 (18.81 GB)
telemt_user_octets_to_client{user="hello"} 62185807192 (57.92 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 77864.8 (21h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 719404
telemt_connections_bad_total 11397
telemt_handshake_timeouts_total 14959
telemt_upstream_connect_attempt_total 79743
telemt_upstream_connect_success_total 79354
telemt_upstream_connect_fail_total 389
telemt_upstream_connect_attempts_per_request{bucket="1"} 79743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10599
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 314
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 389
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 32352
telemt_me_reconnect_success_total 12059
telemt_me_reader_eof_total 13334
telemt_me_idle_close_by_peer_total 13333
telemt_me_route_drop_no_conn_total 266187
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 559733
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1894
telemt_desync_full_logged_total 642
telemt_desync_suppressed_total 1252
telemt_desync_frames_bucket_total{bucket="1_2"} 478
telemt_desync_frames_bucket_total{bucket="3_10"} 853
telemt_desync_frames_bucket_total{bucket="gt_10"} 563
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 12902
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12050
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 843
telemt_user_connections_total{user="hello"} 622882
telemt_user_connections_current{user="hello"} 1269
telemt_user_octets_from_client{user="hello"} 7303568443 (6.80 GB)
telemt_user_octets_to_client{user="hello"} 184450438685 (171.78 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 77837.1 (21h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 319651
telemt_connections_bad_total 59040
telemt_handshake_timeouts_total 3807
telemt_upstream_connect_attempt_total 25516
telemt_upstream_connect_success_total 25030
telemt_upstream_connect_fail_total 486
telemt_upstream_connect_attempts_per_request{bucket="1"} 25516
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11725
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 304
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 486
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 48367
telemt_me_reconnect_success_total 17079
telemt_me_reader_eof_total 18645
telemt_me_idle_close_by_peer_total 18643
telemt_me_route_drop_no_conn_total 91895
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 239664
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1148
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 898
telemt_desync_frames_bucket_total{bucket="1_2"} 573
telemt_desync_frames_bucket_total{bucket="3_10"} 444
telemt_desync_frames_bucket_total{bucket="gt_10"} 131
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 18337
telemt_me_refill_failed_total 973
telemt_me_writer_restored_same_endpoint_total 17071
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1258
telemt_user_connections_total{user="hello"} 243887
telemt_user_connections_current{user="hello"} 738
telemt_user_octets_from_client{user="hello"} 2961069808 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 88326454791 (82.26 GB)
telemt_user_msgs_from_client{user="hello"} 50986
telemt_user_msgs_to_client{user="hello"} 286529
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 78000.1 (21h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 769768
telemt_connections_bad_total 60194
telemt_handshake_timeouts_total 7237
telemt_upstream_connect_attempt_total 15723
telemt_upstream_connect_success_total 15638
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 15723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8046
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 22019
telemt_me_reconnect_success_total 11715
telemt_me_reader_eof_total 12738
telemt_me_idle_close_by_peer_total 12736
telemt_me_route_drop_no_conn_total 573843
telemt_me_route_drop_channel_closed_total 63
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 790007
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1240
telemt_desync_full_logged_total 441
telemt_desync_suppressed_total 799
telemt_desync_frames_bucket_total{bucket="1_2"} 292
telemt_desync_frames_bucket_total{bucket="3_10"} 482
telemt_desync_frames_bucket_total{bucket="gt_10"} 466
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 12227
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 11701
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 512
telemt_user_connections_total{user="hello"} 663756
telemt_user_connections_current{user="hello"} 938
telemt_user_octets_from_client{user="hello"} 9601591472 (8.94 GB)
telemt_user_octets_to_client{user="hello"} 297875198260 (277.42 GB)
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 25764.7 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22326
telemt_connections_bad_total 243
telemt_handshake_timeouts_total 320
telemt_upstream_connect_attempt_total 13655
telemt_upstream_connect_success_total 13538
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 13655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6167
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 23633
telemt_me_reconnect_success_total 12061
telemt_me_reader_eof_total 12761
telemt_me_idle_close_by_peer_total 12761
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 10394
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21169
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 12559
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 12041
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 498
telemt_user_connections_total{user="hello"} 21222
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 725730997 (692.11 MB)
telemt_user_octets_to_client{user="hello"} 28516135358 (26.56 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 37
```