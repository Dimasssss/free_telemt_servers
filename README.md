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

# Server Metrics 2026-03-19 09:12:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 41044.3 (11h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 829185
telemt_connections_bad_total 79091
telemt_connections_current 1654
telemt_connections_me_current 1654
telemt_handshake_timeouts_total 33142
telemt_upstream_connect_attempt_total 7820
telemt_upstream_connect_success_total 7683
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 7820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3958
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 6781
telemt_me_reconnect_success_total 5626
telemt_me_reader_eof_total 5956
telemt_me_idle_close_by_peer_total 5955
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 276974
telemt_me_route_drop_channel_closed_total 103
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 641640
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 29
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4001
telemt_desync_full_logged_total 1198
telemt_desync_suppressed_total 2803
telemt_desync_frames_bucket_total{bucket="1_2"} 1343
telemt_desync_frames_bucket_total{bucket="3_10"} 1467
telemt_desync_frames_bucket_total{bucket="gt_10"} 1191
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5726
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 5607
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 637480
telemt_user_connections_current{user="hello"} 1654
telemt_user_octets_from_client{user="hello"} 10078562868 (9.39 GB)
telemt_user_octets_to_client{user="hello"} 208409205168 (194.10 GB)
telemt_user_unique_ips_current{user="hello"} 561
telemt_user_unique_ips_recent_window{user="hello"} 247
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 41048.0 (11h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2030006
telemt_connections_bad_total 108502
telemt_connections_current 4264
telemt_connections_me_current 4264
telemt_handshake_timeouts_total 45351
telemt_upstream_connect_attempt_total 7818
telemt_upstream_connect_success_total 7672
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 7818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3825
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 7876
telemt_me_reconnect_success_total 5595
telemt_me_reader_eof_total 5948
telemt_me_idle_close_by_peer_total 5948
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 906771
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1689569
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7479
telemt_desync_full_logged_total 2540
telemt_desync_suppressed_total 4939
telemt_desync_frames_bucket_total{bucket="1_2"} 1352
telemt_desync_frames_bucket_total{bucket="3_10"} 2881
telemt_desync_frames_bucket_total{bucket="gt_10"} 3246
telemt_pool_swap_total 31
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 5766
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 5573
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 1689344
telemt_user_connections_current{user="hello"} 4264
telemt_user_octets_from_client{user="hello"} 27918707184 (26.00 GB)
telemt_user_octets_to_client{user="hello"} 631361523016 (588.00 GB)
telemt_user_unique_ips_current{user="hello"} 1455
telemt_user_unique_ips_recent_window{user="hello"} 664
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 41045.7 (11h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1733440
telemt_connections_bad_total 210875
telemt_connections_current 3306
telemt_connections_me_current 3306
telemt_handshake_timeouts_total 42363
telemt_upstream_connect_attempt_total 7334
telemt_upstream_connect_success_total 7334
telemt_upstream_connect_attempts_per_request{bucket="1"} 7334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3480
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 5290
telemt_me_reconnect_success_total 5258
telemt_me_reader_eof_total 5563
telemt_me_idle_close_by_peer_total 5563
telemt_me_route_drop_no_conn_total 806886
telemt_me_route_drop_channel_closed_total 56
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1344639
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6118
telemt_desync_full_logged_total 1915
telemt_desync_suppressed_total 4203
telemt_desync_frames_bucket_total{bucket="1_2"} 1388
telemt_desync_frames_bucket_total{bucket="3_10"} 2212
telemt_desync_frames_bucket_total{bucket="gt_10"} 2518
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 5352
telemt_me_writer_restored_same_endpoint_total 5242
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 1343898
telemt_user_connections_current{user="hello"} 3306
telemt_user_octets_from_client{user="hello"} 21126822788 (19.68 GB)
telemt_user_octets_to_client{user="hello"} 629650408612 (586.41 GB)
telemt_user_unique_ips_current{user="hello"} 1075
telemt_user_unique_ips_recent_window{user="hello"} 539
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 41098.5 (11h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1809184
telemt_connections_bad_total 99676
telemt_connections_current 3196
telemt_connections_me_current 3196
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 45839
telemt_upstream_connect_attempt_total 15562
telemt_upstream_connect_success_total 15453
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 15561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4255
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7628
telemt_me_reconnect_success_total 5221
telemt_me_reader_eof_total 5549
telemt_me_idle_close_by_peer_total 5548
telemt_me_route_drop_no_conn_total 914336
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1336120
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4823
telemt_desync_full_logged_total 1652
telemt_desync_suppressed_total 3171
telemt_desync_frames_bucket_total{bucket="1_2"} 977
telemt_desync_frames_bucket_total{bucket="3_10"} 1895
telemt_desync_frames_bucket_total{bucket="gt_10"} 1951
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5489
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 5197
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 1342798
telemt_user_connections_current{user="hello"} 3196
telemt_user_octets_from_client{user="hello"} 16150697380 (15.04 GB)
telemt_user_octets_to_client{user="hello"} 393727073626 (366.69 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1037
telemt_user_unique_ips_recent_window{user="hello"} 466
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 41041.7 (11h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2093544
telemt_connections_bad_total 517215
telemt_connections_current 3695
telemt_connections_me_current 3695
telemt_handshake_timeouts_total 44065
telemt_upstream_connect_attempt_total 7094
telemt_upstream_connect_success_total 7044
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 7094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3431
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 5020
telemt_me_reconnect_success_total 4977
telemt_me_reader_eof_total 5271
telemt_me_idle_close_by_peer_total 5271
telemt_me_route_drop_no_conn_total 596533
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1324889
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6312
telemt_desync_full_logged_total 1964
telemt_desync_suppressed_total 4348
telemt_desync_frames_bucket_total{bucket="1_2"} 1268
telemt_desync_frames_bucket_total{bucket="3_10"} 2786
telemt_desync_frames_bucket_total{bucket="gt_10"} 2258
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 5051
telemt_me_writer_restored_same_endpoint_total 4953
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 1324115
telemt_user_connections_current{user="hello"} 3695
telemt_user_octets_from_client{user="hello"} 25399097936 (23.65 GB)
telemt_user_octets_to_client{user="hello"} 595072927384 (554.20 GB)
telemt_user_unique_ips_current{user="hello"} 1251
telemt_user_unique_ips_recent_window{user="hello"} 568
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 41053.8 (11h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 370826
telemt_connections_bad_total 17421
telemt_connections_current 928
telemt_connections_me_current 928
telemt_handshake_timeouts_total 3061
telemt_upstream_connect_attempt_total 10408
telemt_upstream_connect_success_total 10142
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 10408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 13457
telemt_me_reconnect_success_total 8074
telemt_me_reader_eof_total 8571
telemt_me_idle_close_by_peer_total 8571
telemt_me_route_drop_no_conn_total 190085
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 331270
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 518
telemt_desync_full_logged_total 181
telemt_desync_suppressed_total 337
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 210
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 20
telemt_pool_stale_pick_total 193
telemt_me_writer_removed_unexpected_total 8305
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 8044
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 231
telemt_user_connections_total{user="hello"} 331236
telemt_user_connections_current{user="hello"} 928
telemt_user_octets_from_client{user="hello"} 4763482808 (4.44 GB)
telemt_user_octets_to_client{user="hello"} 136688805204 (127.30 GB)
telemt_user_unique_ips_current{user="hello"} 338
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 41044.3 (11h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1411290
telemt_connections_bad_total 126031
telemt_connections_current 3191
telemt_connections_me_current 3191
telemt_handshake_timeouts_total 61699
telemt_upstream_connect_attempt_total 8324
telemt_upstream_connect_success_total 8323
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3867
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 7596
telemt_me_reconnect_success_total 6249
telemt_me_reader_eof_total 6615
telemt_me_idle_close_by_peer_total 6614
telemt_me_route_drop_no_conn_total 560614
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1170214
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6698
telemt_desync_full_logged_total 2197
telemt_desync_suppressed_total 4501
telemt_desync_frames_bucket_total{bucket="1_2"} 1252
telemt_desync_frames_bucket_total{bucket="3_10"} 2528
telemt_desync_frames_bucket_total{bucket="gt_10"} 2918
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6363
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 6234
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 1169113
telemt_user_connections_current{user="hello"} 3191
telemt_user_octets_from_client{user="hello"} 16274966240 (15.16 GB)
telemt_user_octets_to_client{user="hello"} 577202216128 (537.56 GB)
telemt_user_unique_ips_current{user="hello"} 1008
telemt_user_unique_ips_recent_window{user="hello"} 431
```