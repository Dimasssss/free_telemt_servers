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

# Server Metrics 2026-03-17 15:04:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 73180.8 (20h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 795688
telemt_connections_bad_total 5986
telemt_handshake_timeouts_total 23340
telemt_upstream_connect_attempt_total 17557
telemt_upstream_connect_success_total 17097
telemt_upstream_connect_fail_total 460
telemt_upstream_connect_attempts_per_request{bucket="1"} 17557
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8978
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7969
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 460
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 25814
telemt_me_reconnect_success_total 11112
telemt_me_reader_eof_total 12120
telemt_me_idle_close_by_peer_total 12119
telemt_me_route_drop_no_conn_total 328065
telemt_me_route_drop_channel_closed_total 82
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 722332
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5073
telemt_desync_full_logged_total 1401
telemt_desync_suppressed_total 3672
telemt_desync_frames_bucket_total{bucket="1_2"} 1477
telemt_desync_frames_bucket_total{bucket="3_10"} 2016
telemt_desync_frames_bucket_total{bucket="gt_10"} 1580
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11724
telemt_me_refill_failed_total 454
telemt_me_writer_restored_same_endpoint_total 11090
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 612
telemt_user_connections_total{user="hello"} 724181
telemt_user_connections_current{user="hello"} 929
telemt_user_octets_from_client{user="hello"} 11822896051 (11.01 GB)
telemt_user_octets_to_client{user="hello"} 241180391675 (224.62 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 196
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 73432.5 (20h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 512152
telemt_connections_bad_total 31714
telemt_handshake_timeouts_total 25886
telemt_upstream_connect_attempt_total 81510
telemt_upstream_connect_success_total 81003
telemt_upstream_connect_fail_total 506
telemt_upstream_connect_attempts_per_request{bucket="1"} 81509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63048
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12084
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5869
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 506
telemt_me_keepalive_timeout_total 329
telemt_me_reconnect_attempts_total 37309
telemt_me_reconnect_success_total 13428
telemt_me_reader_eof_total 14730
telemt_me_idle_close_by_peer_total 14730
telemt_me_route_drop_no_conn_total 191903
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 366653
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1473
telemt_desync_full_logged_total 464
telemt_desync_suppressed_total 1009
telemt_desync_frames_bucket_total{bucket="1_2"} 332
telemt_desync_frames_bucket_total{bucket="3_10"} 645
telemt_desync_frames_bucket_total{bucket="gt_10"} 496
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14337
telemt_me_refill_failed_total 742
telemt_me_writer_restored_same_endpoint_total 13412
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 909
telemt_user_connections_total{user="hello"} 430442
telemt_user_connections_current{user="hello"} 794
telemt_user_octets_from_client{user="hello"} 4744718739 (4.42 GB)
telemt_user_octets_to_client{user="hello"} 127183032478 (118.45 GB)
telemt_user_msgs_from_client{user="hello"} 913947
telemt_user_msgs_to_client{user="hello"} 3078003
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 73208.6 (20h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 265128
telemt_connections_bad_total 7832
telemt_handshake_timeouts_total 17518
telemt_upstream_connect_attempt_total 19234
telemt_upstream_connect_success_total 19135
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 19234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10456
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 27815
telemt_me_reconnect_success_total 15402
telemt_me_reader_eof_total 16654
telemt_me_idle_close_by_peer_total 16651
telemt_me_route_drop_no_conn_total 123719
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226032
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 798
telemt_desync_full_logged_total 231
telemt_desync_suppressed_total 567
telemt_desync_frames_bucket_total{bucket="1_2"} 289
telemt_desync_frames_bucket_total{bucket="3_10"} 359
telemt_desync_frames_bucket_total{bucket="gt_10"} 150
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 15998
telemt_me_refill_failed_total 385
telemt_me_writer_restored_same_endpoint_total 15391
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 596
telemt_user_connections_total{user="hello"} 225893
telemt_user_connections_current{user="hello"} 365
telemt_user_octets_from_client{user="hello"} 18292341804 (17.04 GB)
telemt_user_octets_to_client{user="hello"} 56115297120 (52.26 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 73267.7 (20h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 612967
telemt_connections_bad_total 8568
telemt_handshake_timeouts_total 13467
telemt_upstream_connect_attempt_total 16813
telemt_upstream_connect_success_total 16655
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 16813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8171
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 26734
telemt_me_reconnect_success_total 11919
telemt_me_reader_eof_total 13031
telemt_me_idle_close_by_peer_total 13030
telemt_me_route_drop_no_conn_total 238114
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 526643
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1831
telemt_desync_full_logged_total 618
telemt_desync_suppressed_total 1213
telemt_desync_frames_bucket_total{bucket="1_2"} 463
telemt_desync_frames_bucket_total{bucket="3_10"} 817
telemt_desync_frames_bucket_total{bucket="gt_10"} 551
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12589
telemt_me_refill_failed_total 458
telemt_me_writer_restored_same_endpoint_total 11910
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 670
telemt_user_connections_total{user="hello"} 527467
telemt_user_connections_current{user="hello"} 704
telemt_user_octets_from_client{user="hello"} 6476242506 (6.03 GB)
telemt_user_octets_to_client{user="hello"} 166242211439 (154.83 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 73239.7 (20h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 288394
telemt_connections_bad_total 57267
telemt_handshake_timeouts_total 3630
telemt_upstream_connect_attempt_total 21244
telemt_upstream_connect_success_total 20773
telemt_upstream_connect_fail_total 471
telemt_upstream_connect_attempts_per_request{bucket="1"} 21244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11143
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 288
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 471
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 41152
telemt_me_reconnect_success_total 16681
telemt_me_reader_eof_total 18036
telemt_me_idle_close_by_peer_total 18034
telemt_me_route_drop_no_conn_total 81449
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 215361
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1120
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 882
telemt_desync_frames_bucket_total{bucket="1_2"} 560
telemt_desync_frames_bucket_total{bucket="3_10"} 431
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 17725
telemt_me_refill_failed_total 760
telemt_me_writer_restored_same_endpoint_total 16673
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1044
telemt_user_connections_total{user="hello"} 215865
telemt_user_connections_current{user="hello"} 253
telemt_user_octets_from_client{user="hello"} 2714867023 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 78769648039 (73.36 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 73402.2 (20h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 696680
telemt_connections_bad_total 55612
telemt_handshake_timeouts_total 6949
telemt_upstream_connect_attempt_total 14781
telemt_upstream_connect_success_total 14699
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 14781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7449
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 21299
telemt_me_reconnect_success_total 11003
telemt_me_reader_eof_total 11979
telemt_me_idle_close_by_peer_total 11979
telemt_me_route_drop_no_conn_total 502581
telemt_me_route_drop_channel_closed_total 42
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 704715
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 984
telemt_desync_full_logged_total 359
telemt_desync_suppressed_total 625
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 393
telemt_desync_frames_bucket_total{bucket="gt_10"} 342
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 11500
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 10989
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 497
telemt_user_connections_total{user="hello"} 598589
telemt_user_connections_current{user="hello"} 1002
telemt_user_octets_from_client{user="hello"} 8824058240 (8.22 GB)
telemt_user_octets_to_client{user="hello"} 267365651972 (249.00 GB)
telemt_user_unique_ips_current{user="hello"} 336
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 21167.9 (5h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16552
telemt_connections_bad_total 71
telemt_handshake_timeouts_total 309
telemt_upstream_connect_attempt_total 11512
telemt_upstream_connect_success_total 11416
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 11512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6205
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5181
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 21724
telemt_me_reconnect_success_total 10168
telemt_me_reader_eof_total 10765
telemt_me_idle_close_by_peer_total 10765
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 6087
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15758
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 10632
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 10153
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 15856
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 486552817 (464.01 MB)
telemt_user_octets_to_client{user="hello"} 23266754494 (21.67 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 13
```