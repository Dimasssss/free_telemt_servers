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

# Server Metrics 2026-03-17 11:50:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 61535.0 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 560793
telemt_connections_bad_total 4698
telemt_handshake_timeouts_total 17362
telemt_upstream_connect_attempt_total 15255
telemt_upstream_connect_success_total 14811
telemt_upstream_connect_fail_total 444
telemt_upstream_connect_attempts_per_request{bucket="1"} 15255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 444
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 10976
telemt_me_reconnect_success_total 9439
telemt_me_reader_eof_total 10015
telemt_me_idle_close_by_peer_total 10014
telemt_me_route_drop_no_conn_total 182037
telemt_me_route_drop_channel_closed_total 50
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 505964
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3940
telemt_desync_full_logged_total 1047
telemt_desync_suppressed_total 2893
telemt_desync_frames_bucket_total{bucket="1_2"} 1141
telemt_desync_frames_bucket_total{bucket="3_10"} 1642
telemt_desync_frames_bucket_total{bucket="gt_10"} 1157
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 9624
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 9417
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 185
telemt_user_connections_total{user="hello"} 507888
telemt_user_connections_current{user="hello"} 881
telemt_user_octets_from_client{user="hello"} 6876057871 (6.40 GB)
telemt_user_octets_to_client{user="hello"} 183706822783 (171.09 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 61786.8 (17h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 314050
telemt_connections_bad_total 13719
telemt_handshake_timeouts_total 17966
telemt_upstream_connect_attempt_total 15588
telemt_upstream_connect_success_total 15368
telemt_upstream_connect_fail_total 220
telemt_upstream_connect_attempts_per_request{bucket="1"} 15588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8507
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 220
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 24638
telemt_me_reconnect_success_total 12303
telemt_me_reader_eof_total 13276
telemt_me_idle_close_by_peer_total 13276
telemt_me_route_drop_no_conn_total 116113
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 266981
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 883
telemt_desync_full_logged_total 304
telemt_desync_suppressed_total 579
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 371
telemt_desync_frames_bucket_total{bucket="gt_10"} 271
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 12822
telemt_me_refill_failed_total 384
telemt_me_writer_restored_same_endpoint_total 12287
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 519
telemt_user_connections_total{user="hello"} 266975
telemt_user_connections_current{user="hello"} 589
telemt_user_octets_from_client{user="hello"} 3122169328 (2.91 GB)
telemt_user_octets_to_client{user="hello"} 96653242812 (90.02 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 61563.3 (17h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183888
telemt_connections_bad_total 7724
telemt_handshake_timeouts_total 15196
telemt_upstream_connect_attempt_total 16177
telemt_upstream_connect_success_total 16092
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 16177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8893
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 14856
telemt_me_reconnect_success_total 12983
telemt_me_reader_eof_total 13870
telemt_me_idle_close_by_peer_total 13870
telemt_me_route_drop_no_conn_total 55044
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150493
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 549
telemt_desync_full_logged_total 144
telemt_desync_suppressed_total 405
telemt_desync_frames_bucket_total{bucket="1_2"} 235
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 13229
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 12972
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 246
telemt_user_connections_total{user="hello"} 150395
telemt_user_connections_current{user="hello"} 279
telemt_user_octets_from_client{user="hello"} 14507750352 (13.51 GB)
telemt_user_octets_to_client{user="hello"} 43077605036 (40.12 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 61622.1 (17h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 416638
telemt_connections_bad_total 6847
telemt_handshake_timeouts_total 12159
telemt_upstream_connect_attempt_total 14091
telemt_upstream_connect_success_total 13958
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 14091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7337
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 14175
telemt_me_reconnect_success_total 10806
telemt_me_reader_eof_total 11532
telemt_me_idle_close_by_peer_total 11532
telemt_me_route_drop_no_conn_total 117505
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 347430
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1042
telemt_desync_full_logged_total 378
telemt_desync_suppressed_total 664
telemt_desync_frames_bucket_total{bucket="1_2"} 244
telemt_desync_frames_bucket_total{bucket="3_10"} 455
telemt_desync_frames_bucket_total{bucket="gt_10"} 343
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 11085
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 10797
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 279
telemt_user_connections_total{user="hello"} 347363
telemt_user_connections_current{user="hello"} 692
telemt_user_octets_from_client{user="hello"} 4493897114 (4.19 GB)
telemt_user_octets_to_client{user="hello"} 125972683065 (117.32 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 61594.0 (17h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217140
telemt_connections_bad_total 52192
telemt_handshake_timeouts_total 3060
telemt_upstream_connect_attempt_total 18106
telemt_upstream_connect_success_total 17869
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 18106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9624
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 231
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 28318
telemt_me_reconnect_success_total 14661
telemt_me_reader_eof_total 15698
telemt_me_idle_close_by_peer_total 15698
telemt_me_route_drop_no_conn_total 57226
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 154644
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 902
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 725
telemt_desync_frames_bucket_total{bucket="1_2"} 474
telemt_desync_frames_bucket_total{bucket="3_10"} 327
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 15271
telemt_me_refill_failed_total 424
telemt_me_writer_restored_same_endpoint_total 14653
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 610
telemt_user_connections_total{user="hello"} 154659
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 2127359355 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 64621318674 (60.18 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 61756.1 (17h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 512730
telemt_connections_bad_total 51924
telemt_handshake_timeouts_total 4766
telemt_upstream_connect_attempt_total 12480
telemt_upstream_connect_success_total 12413
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 12480
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6261
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 13229
telemt_me_reconnect_success_total 9336
telemt_me_reader_eof_total 10064
telemt_me_idle_close_by_peer_total 10064
telemt_me_route_drop_no_conn_total 339872
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 506032
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 759
telemt_desync_full_logged_total 283
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 200
telemt_desync_frames_bucket_total{bucket="3_10"} 294
telemt_desync_frames_bucket_total{bucket="gt_10"} 265
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 9602
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 9322
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 266
telemt_user_connections_total{user="hello"} 427717
telemt_user_connections_current{user="hello"} 855
telemt_user_octets_from_client{user="hello"} 6368815648 (5.93 GB)
telemt_user_octets_to_client{user="hello"} 214451359040 (199.72 GB)
telemt_user_unique_ips_current{user="hello"} 287
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 9522.1 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7219
telemt_connections_bad_total 42
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 5431
telemt_upstream_connect_success_total 5383
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 5431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2893
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2490
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 7978
telemt_me_reconnect_success_total 4740
telemt_me_reader_eof_total 4948
telemt_me_idle_close_by_peer_total 4948
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 2662
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6878
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 4890
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 4731
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 6984
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 156837877 (149.57 MB)
telemt_user_octets_to_client{user="hello"} 19293494746 (17.97 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 7
```