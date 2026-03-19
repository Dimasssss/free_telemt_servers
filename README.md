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

# Server Metrics 2026-03-19 07:20:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 34294.1 (9h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 589143
telemt_connections_bad_total 61164
telemt_connections_current 1356
telemt_connections_me_current 1356
telemt_handshake_timeouts_total 23505
telemt_upstream_connect_attempt_total 6650
telemt_upstream_connect_success_total 6526
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 6650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3347
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 67
telemt_me_reconnect_attempts_total 5942
telemt_me_reconnect_success_total 4792
telemt_me_reader_eof_total 5078
telemt_me_idle_close_by_peer_total 5077
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 166430
telemt_me_route_drop_channel_closed_total 57
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 441760
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2941
telemt_desync_full_logged_total 827
telemt_desync_suppressed_total 2114
telemt_desync_frames_bucket_total{bucket="1_2"} 1044
telemt_desync_frames_bucket_total{bucket="3_10"} 1103
telemt_desync_frames_bucket_total{bucket="gt_10"} 794
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 4880
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 4775
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 438885
telemt_user_connections_current{user="hello"} 1356
telemt_user_octets_from_client{user="hello"} 5906797144 (5.50 GB)
telemt_user_octets_to_client{user="hello"} 148173289788 (138.00 GB)
telemt_user_unique_ips_current{user="hello"} 474
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 34297.7 (9h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1364289
telemt_connections_bad_total 78326
telemt_connections_current 3906
telemt_connections_me_current 3906
telemt_handshake_timeouts_total 32640
telemt_upstream_connect_attempt_total 6464
telemt_upstream_connect_success_total 6339
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 6464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 5747
telemt_me_reconnect_success_total 4593
telemt_me_reader_eof_total 4870
telemt_me_idle_close_by_peer_total 4870
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 579743
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1123188
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4924
telemt_desync_full_logged_total 1667
telemt_desync_suppressed_total 3257
telemt_desync_frames_bucket_total{bucket="1_2"} 900
telemt_desync_frames_bucket_total{bucket="3_10"} 1837
telemt_desync_frames_bucket_total{bucket="gt_10"} 2187
telemt_pool_swap_total 28
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4715
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 4572
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 1123119
telemt_user_connections_current{user="hello"} 3906
telemt_user_octets_from_client{user="hello"} 21255213032 (19.80 GB)
telemt_user_octets_to_client{user="hello"} 456975719968 (425.59 GB)
telemt_user_unique_ips_current{user="hello"} 1336
telemt_user_unique_ips_recent_window{user="hello"} 582
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 34295.0 (9h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1160351
telemt_connections_bad_total 166987
telemt_connections_current 3133
telemt_connections_me_current 3133
telemt_handshake_timeouts_total 32072
telemt_upstream_connect_attempt_total 6201
telemt_upstream_connect_success_total 6201
telemt_upstream_connect_attempts_per_request{bucket="1"} 6201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2998
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 4475
telemt_me_reconnect_success_total 4452
telemt_me_reader_eof_total 4710
telemt_me_idle_close_by_peer_total 4710
telemt_me_route_drop_no_conn_total 504246
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 870925
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4062
telemt_desync_full_logged_total 1275
telemt_desync_suppressed_total 2787
telemt_desync_frames_bucket_total{bucket="1_2"} 794
telemt_desync_frames_bucket_total{bucket="3_10"} 1463
telemt_desync_frames_bucket_total{bucket="gt_10"} 1805
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 4534
telemt_me_writer_restored_same_endpoint_total 4436
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 870566
telemt_user_connections_current{user="hello"} 3133
telemt_user_octets_from_client{user="hello"} 15465868236 (14.40 GB)
telemt_user_octets_to_client{user="hello"} 442086989836 (411.73 GB)
telemt_user_unique_ips_current{user="hello"} 1030
telemt_user_unique_ips_recent_window{user="hello"} 453
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 34348.1 (9h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1206752
telemt_connections_bad_total 89555
telemt_connections_current 2884
telemt_connections_me_current 2884
telemt_handshake_timeouts_total 30491
telemt_upstream_connect_attempt_total 6012
telemt_upstream_connect_success_total 6012
telemt_upstream_connect_attempts_per_request{bucket="1"} 6012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3046
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2951
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 5312
telemt_me_reconnect_success_total 4251
telemt_me_reader_eof_total 4523
telemt_me_idle_close_by_peer_total 4522
telemt_me_route_drop_no_conn_total 432660
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 825463
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3127
telemt_desync_full_logged_total 1096
telemt_desync_suppressed_total 2031
telemt_desync_frames_bucket_total{bucket="1_2"} 583
telemt_desync_frames_bucket_total{bucket="3_10"} 1232
telemt_desync_frames_bucket_total{bucket="gt_10"} 1312
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 4345
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 4227
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 824304
telemt_user_connections_current{user="hello"} 2884
telemt_user_octets_from_client{user="hello"} 12070643008 (11.24 GB)
telemt_user_octets_to_client{user="hello"} 294346007212 (274.13 GB)
telemt_user_unique_ips_current{user="hello"} 962
telemt_user_unique_ips_recent_window{user="hello"} 397
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 34291.2 (9h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1463146
telemt_connections_bad_total 414682
telemt_connections_current 3196
telemt_connections_me_current 3196
telemt_handshake_timeouts_total 31880
telemt_upstream_connect_attempt_total 6054
telemt_upstream_connect_success_total 6017
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 6054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2938
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 4306
telemt_me_reconnect_success_total 4274
telemt_me_reader_eof_total 4523
telemt_me_idle_close_by_peer_total 4523
telemt_me_route_drop_no_conn_total 363967
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 874321
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4326
telemt_desync_full_logged_total 1351
telemt_desync_suppressed_total 2975
telemt_desync_frames_bucket_total{bucket="1_2"} 966
telemt_desync_frames_bucket_total{bucket="3_10"} 1950
telemt_desync_frames_bucket_total{bucket="gt_10"} 1410
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 4328
telemt_me_writer_restored_same_endpoint_total 4250
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 874031
telemt_user_connections_current{user="hello"} 3196
telemt_user_octets_from_client{user="hello"} 19139461632 (17.83 GB)
telemt_user_octets_to_client{user="hello"} 437302111088 (407.27 GB)
telemt_user_unique_ips_current{user="hello"} 1095
telemt_user_unique_ips_recent_window{user="hello"} 500
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 34303.0 (9h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244787
telemt_connections_bad_total 13044
telemt_connections_current 803
telemt_connections_me_current 803
telemt_handshake_timeouts_total 2179
telemt_upstream_connect_attempt_total 9061
telemt_upstream_connect_success_total 8827
telemt_upstream_connect_fail_total 234
telemt_upstream_connect_attempts_per_request{bucket="1"} 9061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4488
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 234
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 12456
telemt_me_reconnect_success_total 7083
telemt_me_reader_eof_total 7514
telemt_me_idle_close_by_peer_total 7514
telemt_me_route_drop_no_conn_total 116151
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 216879
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 352
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 234
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 149
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 7291
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 7053
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 216858
telemt_user_connections_current{user="hello"} 803
telemt_user_octets_from_client{user="hello"} 3360687864 (3.13 GB)
telemt_user_octets_to_client{user="hello"} 109388249876 (101.88 GB)
telemt_user_unique_ips_current{user="hello"} 311
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 34293.9 (9h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 919662
telemt_connections_bad_total 90289
telemt_connections_current 2749
telemt_connections_me_current 2749
telemt_handshake_timeouts_total 39450
telemt_upstream_connect_attempt_total 7031
telemt_upstream_connect_success_total 7031
telemt_upstream_connect_attempts_per_request{bucket="1"} 7031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3284
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 6619
telemt_me_reconnect_success_total 5287
telemt_me_reader_eof_total 5599
telemt_me_idle_close_by_peer_total 5599
telemt_me_route_drop_no_conn_total 376062
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 755284
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4356
telemt_desync_full_logged_total 1471
telemt_desync_suppressed_total 2885
telemt_desync_frames_bucket_total{bucket="1_2"} 875
telemt_desync_frames_bucket_total{bucket="3_10"} 1664
telemt_desync_frames_bucket_total{bucket="gt_10"} 1817
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5384
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 5272
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 754383
telemt_user_connections_current{user="hello"} 2749
telemt_user_octets_from_client{user="hello"} 10937079932 (10.19 GB)
telemt_user_octets_to_client{user="hello"} 417545969728 (388.87 GB)
telemt_user_unique_ips_current{user="hello"} 936
telemt_user_unique_ips_recent_window{user="hello"} 409
```