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

# Server Metrics 2026-03-19 09:07:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 40737.0 (11h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 818228
telemt_connections_bad_total 78487
telemt_connections_current 1730
telemt_connections_me_current 1730
telemt_handshake_timeouts_total 33037
telemt_upstream_connect_attempt_total 7751
telemt_upstream_connect_success_total 7614
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 7751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3920
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 6712
telemt_me_reconnect_success_total 5557
telemt_me_reader_eof_total 5887
telemt_me_idle_close_by_peer_total 5886
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 270855
telemt_me_route_drop_channel_closed_total 102
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 631589
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 29
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3956
telemt_desync_full_logged_total 1185
telemt_desync_suppressed_total 2771
telemt_desync_frames_bucket_total{bucket="1_2"} 1331
telemt_desync_frames_bucket_total{bucket="3_10"} 1450
telemt_desync_frames_bucket_total{bucket="gt_10"} 1175
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5657
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 5538
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 627850
telemt_user_connections_current{user="hello"} 1730
telemt_user_octets_from_client{user="hello"} 9970962212 (9.29 GB)
telemt_user_octets_to_client{user="hello"} 206129753760 (191.97 GB)
telemt_user_unique_ips_current{user="hello"} 548
telemt_user_unique_ips_recent_window{user="hello"} 279
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 40742.1 (11h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1999159
telemt_connections_bad_total 107851
telemt_connections_current 4489
telemt_connections_me_current 4489
telemt_handshake_timeouts_total 44861
telemt_upstream_connect_attempt_total 7773
telemt_upstream_connect_success_total 7627
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 7773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3804
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 7575
telemt_me_reconnect_success_total 5550
telemt_me_reader_eof_total 5893
telemt_me_idle_close_by_peer_total 5893
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 888994
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1661634
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7341
telemt_desync_full_logged_total 2501
telemt_desync_suppressed_total 4840
telemt_desync_frames_bucket_total{bucket="1_2"} 1324
telemt_desync_frames_bucket_total{bucket="3_10"} 2826
telemt_desync_frames_bucket_total{bucket="gt_10"} 3191
telemt_pool_swap_total 31
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 5711
telemt_me_refill_failed_total 63
telemt_me_writer_restored_same_endpoint_total 5528
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 1661408
telemt_user_connections_current{user="hello"} 4489
telemt_user_octets_from_client{user="hello"} 27687658576 (25.79 GB)
telemt_user_octets_to_client{user="hello"} 621324724984 (578.65 GB)
telemt_user_unique_ips_current{user="hello"} 1479
telemt_user_unique_ips_recent_window{user="hello"} 708
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 40792.3 (11h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1783674
telemt_connections_bad_total 99234
telemt_connections_current 3499
telemt_connections_me_current 3499
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 45215
telemt_upstream_connect_attempt_total 15520
telemt_upstream_connect_success_total 15415
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 15520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4242
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7586
telemt_me_reconnect_success_total 5184
telemt_me_reader_eof_total 5508
telemt_me_idle_close_by_peer_total 5507
telemt_me_route_drop_no_conn_total 902696
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1312866
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4711
telemt_desync_full_logged_total 1612
telemt_desync_suppressed_total 3099
telemt_desync_frames_bucket_total{bucket="1_2"} 960
telemt_desync_frames_bucket_total{bucket="3_10"} 1847
telemt_desync_frames_bucket_total{bucket="gt_10"} 1904
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5448
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 5160
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 264
telemt_user_connections_total{user="hello"} 1319586
telemt_user_connections_current{user="hello"} 3499
telemt_user_octets_from_client{user="hello"} 15976051784 (14.88 GB)
telemt_user_octets_to_client{user="hello"} 388110906530 (361.46 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1048
telemt_user_unique_ips_recent_window{user="hello"} 497
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 40735.7 (11h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2063533
telemt_connections_bad_total 515542
telemt_connections_current 3813
telemt_connections_me_current 3813
telemt_handshake_timeouts_total 43117
telemt_upstream_connect_attempt_total 7037
telemt_upstream_connect_success_total 6987
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 7037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3406
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 4963
telemt_me_reconnect_success_total 4921
telemt_me_reader_eof_total 5215
telemt_me_idle_close_by_peer_total 5215
telemt_me_route_drop_no_conn_total 581053
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1300731
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6244
telemt_desync_full_logged_total 1936
telemt_desync_suppressed_total 4308
telemt_desync_frames_bucket_total{bucket="1_2"} 1265
telemt_desync_frames_bucket_total{bucket="3_10"} 2758
telemt_desync_frames_bucket_total{bucket="gt_10"} 2221
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 4995
telemt_me_writer_restored_same_endpoint_total 4897
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 1299968
telemt_user_connections_current{user="hello"} 3813
telemt_user_octets_from_client{user="hello"} 25182570404 (23.45 GB)
telemt_user_octets_to_client{user="hello"} 587498984992 (547.15 GB)
telemt_user_unique_ips_current{user="hello"} 1281
telemt_user_unique_ips_recent_window{user="hello"} 632
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 40748.3 (11h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 365369
telemt_connections_bad_total 17387
telemt_connections_current 910
telemt_connections_me_current 910
telemt_handshake_timeouts_total 3021
telemt_upstream_connect_attempt_total 10357
telemt_upstream_connect_success_total 10091
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 10357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5078
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 13406
telemt_me_reconnect_success_total 8023
telemt_me_reader_eof_total 8520
telemt_me_idle_close_by_peer_total 8520
telemt_me_route_drop_no_conn_total 187296
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 326034
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 502
telemt_desync_full_logged_total 175
telemt_desync_suppressed_total 327
telemt_desync_frames_bucket_total{bucket="1_2"} 136
telemt_desync_frames_bucket_total{bucket="3_10"} 202
telemt_desync_frames_bucket_total{bucket="gt_10"} 164
telemt_pool_swap_total 20
telemt_pool_stale_pick_total 193
telemt_me_writer_removed_unexpected_total 8254
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 7993
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 231
telemt_user_connections_total{user="hello"} 325999
telemt_user_connections_current{user="hello"} 910
telemt_user_octets_from_client{user="hello"} 4707612308 (4.38 GB)
telemt_user_octets_to_client{user="hello"} 135213275344 (125.93 GB)
telemt_user_unique_ips_current{user="hello"} 332
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 40738.0 (11h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1390642
telemt_connections_bad_total 125072
telemt_connections_current 3099
telemt_connections_me_current 3099
telemt_handshake_timeouts_total 60926
telemt_upstream_connect_attempt_total 8234
telemt_upstream_connect_success_total 8233
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3822
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 7506
telemt_me_reconnect_success_total 6159
telemt_me_reader_eof_total 6525
telemt_me_idle_close_by_peer_total 6524
telemt_me_route_drop_no_conn_total 551837
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1151920
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6648
telemt_desync_full_logged_total 2179
telemt_desync_suppressed_total 4469
telemt_desync_frames_bucket_total{bucket="1_2"} 1245
telemt_desync_frames_bucket_total{bucket="3_10"} 2510
telemt_desync_frames_bucket_total{bucket="gt_10"} 2893
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6273
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 6144
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 1150822
telemt_user_connections_current{user="hello"} 3099
telemt_user_octets_from_client{user="hello"} 16089130504 (14.98 GB)
telemt_user_octets_to_client{user="hello"} 568443245832 (529.40 GB)
telemt_user_unique_ips_current{user="hello"} 1032
telemt_user_unique_ips_recent_window{user="hello"} 541
```