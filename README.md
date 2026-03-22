# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-22 00:23:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 11819.7 (3h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180033
telemt_connections_bad_total 12101
telemt_connections_current 713
telemt_connections_me_current 713
telemt_handshake_timeouts_total 10035
telemt_upstream_connect_attempt_total 4849
telemt_upstream_connect_success_total 4848
telemt_upstream_connect_attempts_per_request{bucket="1"} 4848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3020
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 149
telemt_me_reconnect_success_total 77
telemt_me_reader_eof_total 78
telemt_me_idle_close_by_peer_total 78
telemt_me_route_drop_no_conn_total 36267
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147565
telemt_me_endpoint_quarantine_total 83
telemt_me_single_endpoint_shadow_rotate_total 102
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 1034
telemt_desync_full_logged_total 298
telemt_desync_suppressed_total 736
telemt_desync_frames_bucket_total{bucket="1_2"} 266
telemt_desync_frames_bucket_total{bucket="3_10"} 342
telemt_desync_frames_bucket_total{bucket="gt_10"} 426
telemt_pool_swap_total 13
telemt_pool_force_close_total 326
telemt_me_writer_close_signal_drop_total 22
telemt_me_draining_writers_reap_progress_total 4312
telemt_me_writer_removed_unexpected_total 74
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 317
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4057
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 322
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3986
telemt_me_writer_teardown_success_total{mode="normal"} 4374
telemt_me_writer_teardown_noop_total 4313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 8385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 8562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 8616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 8661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 8685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 8687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 8687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 8687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 8687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 8687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 8687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 8687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 8687
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.659203
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 8687
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 22
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 70
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 147373
telemt_user_connections_current{user="hello"} 713
telemt_user_octets_from_client{user="hello"} 1697279336 (1.58 GB)
telemt_user_octets_to_client{user="hello"} 50975226956 (47.47 GB)
telemt_user_unique_ips_current{user="hello"} 311
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 25186.2 (6h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 690779
telemt_connections_bad_total 39880
telemt_connections_current 675
telemt_connections_me_current 675
telemt_handshake_timeouts_total 26172
telemt_upstream_connect_attempt_total 10786
telemt_upstream_connect_success_total 10599
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 10768
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5802
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_reconnect_attempts_total 931
telemt_me_reconnect_success_total 326
telemt_me_reader_eof_total 280
telemt_me_idle_close_by_peer_total 280
telemt_me_route_drop_no_conn_total 328946
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 558087
telemt_me_endpoint_quarantine_total 225
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 203
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 2439
telemt_desync_full_logged_total 1401
telemt_desync_suppressed_total 1038
telemt_desync_frames_bucket_total{bucket="1_2"} 522
telemt_desync_frames_bucket_total{bucket="3_10"} 911
telemt_desync_frames_bucket_total{bucket="gt_10"} 1006
telemt_pool_swap_total 27
telemt_pool_force_close_total 748
telemt_me_writer_close_signal_drop_total 57
telemt_me_draining_writers_reap_progress_total 9506
telemt_me_writer_removed_unexpected_total 263
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 828
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8945
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 741
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8758
telemt_me_writer_teardown_success_total{mode="normal"} 9773
telemt_me_writer_teardown_noop_total 9506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 18818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 19087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 19173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 19265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 19277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 19279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 19279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 19279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 19279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 19279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 19279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 19279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 19279
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.388161
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 19279
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 57
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 225
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 557281
telemt_user_connections_current{user="hello"} 675
telemt_user_octets_from_client{user="hello"} 9269238944 (8.63 GB)
telemt_user_octets_to_client{user="hello"} 195854680376 (182.40 GB)
telemt_user_unique_ips_current{user="hello"} 417
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 100046.3 (27h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7489946
telemt_connections_bad_total 598320
telemt_connections_current 1882
telemt_connections_me_current 1882
telemt_handshake_timeouts_total 243754
telemt_upstream_connect_attempt_total 36383
telemt_upstream_connect_success_total 36313
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 36320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19694
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1499
telemt_me_reconnect_success_total 751
telemt_me_reader_eof_total 761
telemt_me_idle_close_by_peer_total 761
telemt_me_route_drop_no_conn_total 4505582
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6103096
telemt_me_endpoint_quarantine_total 635
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 742
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 25884
telemt_desync_full_logged_total 8560
telemt_desync_suppressed_total 17324
telemt_desync_frames_bucket_total{bucket="1_2"} 5570
telemt_desync_frames_bucket_total{bucket="3_10"} 10097
telemt_desync_frames_bucket_total{bucket="gt_10"} 10217
telemt_pool_swap_total 108
telemt_pool_force_close_total 3608
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 576
telemt_me_draining_writers_reap_progress_total 33151
telemt_me_writer_removed_unexpected_total 731
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2804
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30637
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3369
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29543
telemt_me_writer_teardown_success_total{mode="normal"} 33441
telemt_me_writer_teardown_noop_total 33195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66636
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 153.646598
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66636
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 576
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 671
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 6095455
telemt_user_connections_current{user="hello"} 1882
telemt_user_octets_from_client{user="hello"} 104396134744 (97.23 GB)
telemt_user_octets_to_client{user="hello"} 2009279829392 (1.83 TB)
telemt_user_unique_ips_current{user="hello"} 893
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 100047.5 (27h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6165735
telemt_connections_bad_total 580079
telemt_connections_current 1216
telemt_connections_me_current 1216
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 203374
telemt_upstream_connect_attempt_total 40522
telemt_upstream_connect_success_total 40141
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 40326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19472
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1848
telemt_me_reconnect_success_total 811
telemt_me_reader_eof_total 787
telemt_me_idle_close_by_peer_total 787
telemt_me_route_drop_no_conn_total 2197634
telemt_me_route_drop_channel_closed_total 255
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4620594
telemt_me_endpoint_quarantine_total 617
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 763
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 22160
telemt_desync_full_logged_total 7504
telemt_desync_suppressed_total 14656
telemt_desync_frames_bucket_total{bucket="1_2"} 5338
telemt_desync_frames_bucket_total{bucket="3_10"} 8594
telemt_desync_frames_bucket_total{bucket="gt_10"} 8228
telemt_pool_swap_total 109
telemt_pool_force_close_total 3260
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 347
telemt_me_draining_writers_reap_progress_total 31822
telemt_me_writer_removed_unexpected_total 766
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2724
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29799
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3047
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28562
telemt_me_writer_teardown_success_total{mode="normal"} 32523
telemt_me_writer_teardown_noop_total 31828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64351
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.028998
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64351
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 347
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 707
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 4557622
telemt_user_connections_current{user="hello"} 1216
telemt_user_octets_from_client{user="hello"} 138417631057 (128.91 GB)
telemt_user_octets_to_client{user="hello"} 2135383069139 (1.94 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 620
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 100011.4 (27h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6070945
telemt_connections_bad_total 540754
telemt_connections_current 1478
telemt_connections_me_current 1478
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 194557
telemt_upstream_connect_attempt_total 46806
telemt_upstream_connect_success_total 46490
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 46625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24205
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20862
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 372
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1051
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1823
telemt_me_reconnect_success_total 836
telemt_me_reader_eof_total 782
telemt_me_idle_close_by_peer_total 782
telemt_me_route_drop_no_conn_total 2111064
telemt_me_route_drop_channel_closed_total 109
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4531964
telemt_me_endpoint_quarantine_total 682
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 748
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 22014
telemt_desync_full_logged_total 7347
telemt_desync_suppressed_total 14667
telemt_desync_frames_bucket_total{bucket="1_2"} 5383
telemt_desync_frames_bucket_total{bucket="3_10"} 8430
telemt_desync_frames_bucket_total{bucket="gt_10"} 8201
telemt_pool_swap_total 108
telemt_pool_force_close_total 3150
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 369
telemt_me_draining_writers_reap_progress_total 33187
telemt_me_writer_removed_unexpected_total 748
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2768
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31176
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2935
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30037
telemt_me_writer_teardown_success_total{mode="normal"} 33944
telemt_me_writer_teardown_noop_total 33198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67142
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.540202
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67142
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 369
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 724
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 4532915
telemt_user_connections_current{user="hello"} 1478
telemt_user_octets_from_client{user="hello"} 132018279587 (122.95 GB)
telemt_user_octets_to_client{user="hello"} 2077298370047 (1.89 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 762
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 100050.1 (27h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20049394
telemt_connections_bad_total 1498459
telemt_connections_current 2149
telemt_connections_me_current 2149
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 581212
telemt_upstream_connect_attempt_total 189834
telemt_upstream_connect_success_total 172179
telemt_upstream_connect_fail_total 16039
telemt_upstream_connect_attempts_per_request{bucket="1"} 188218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40389
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8886
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16039
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64371
telemt_me_reconnect_success_total 2175
telemt_me_reader_eof_total 1362
telemt_me_idle_close_by_peer_total 1361
telemt_me_route_drop_no_conn_total 39460821
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16301353
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 771
telemt_me_single_endpoint_outage_enter_total 123
telemt_me_single_endpoint_outage_exit_total 123
telemt_me_single_endpoint_outage_reconnect_attempt_total 259
telemt_me_single_endpoint_outage_reconnect_success_total 62
telemt_me_single_endpoint_quarantine_bypass_total 259
telemt_me_single_endpoint_shadow_rotate_total 782
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 31414
telemt_desync_full_logged_total 9353
telemt_desync_suppressed_total 22061
telemt_desync_frames_bucket_total{bucket="1_2"} 6840
telemt_desync_frames_bucket_total{bucket="3_10"} 13910
telemt_desync_frames_bucket_total{bucket="gt_10"} 10664
telemt_pool_swap_total 103
telemt_pool_force_close_total 3380
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 764
telemt_me_draining_writers_reap_progress_total 31089
telemt_me_writer_removed_unexpected_total 2021
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4249
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28597
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2861
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 519
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27709
telemt_me_writer_teardown_success_total{mode="normal"} 32846
telemt_me_writer_teardown_noop_total 31115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63961
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 212.278734
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63961
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 764
telemt_me_refill_failed_total 3789
telemt_me_writer_restored_same_endpoint_total 1508
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 492
telemt_user_connections_total{user="hello"} 16429153
telemt_user_connections_current{user="hello"} 2149
telemt_user_octets_from_client{user="hello"} 191440633236 (178.29 GB)
telemt_user_octets_to_client{user="hello"} 1135021470850 (1.03 TB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 914
telemt_user_unique_ips_recent_window{user="hello"} 254
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 100017.8 (27h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5861013
telemt_connections_bad_total 552582
telemt_connections_current 1551
telemt_connections_me_current 1551
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 121066
telemt_upstream_connect_attempt_total 54944
telemt_upstream_connect_success_total 54315
telemt_upstream_connect_fail_total 538
telemt_upstream_connect_attempts_per_request{bucket="1"} 54853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21738
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 538
telemt_me_reconnect_attempts_total 68131
telemt_me_reconnect_success_total 1696
telemt_me_reader_eof_total 1475
telemt_me_idle_close_by_peer_total 1474
telemt_me_route_drop_no_conn_total 2363479
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4569051
telemt_me_endpoint_quarantine_total 671
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 748
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 42
telemt_desync_total 23031
telemt_desync_full_logged_total 8076
telemt_desync_suppressed_total 14955
telemt_desync_frames_bucket_total{bucket="1_2"} 4366
telemt_desync_frames_bucket_total{bucket="3_10"} 8920
telemt_desync_frames_bucket_total{bucket="gt_10"} 9745
telemt_pool_swap_total 103
telemt_pool_force_close_total 2996
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 379
telemt_me_draining_writers_reap_progress_total 34564
telemt_me_writer_removed_unexpected_total 1520
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3656
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32452
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2595
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31568
telemt_me_writer_teardown_success_total{mode="normal"} 36108
telemt_me_writer_teardown_noop_total 34565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70673
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.972803
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70673
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 379
telemt_me_refill_failed_total 4120
telemt_me_writer_restored_same_endpoint_total 1431
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 223
telemt_me_async_recovery_trigger_total 7257
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 4562139
telemt_user_connections_current{user="hello"} 1551
telemt_user_octets_from_client{user="hello"} 122525015872 (114.11 GB)
telemt_user_octets_to_client{user="hello"} 1865154733822 (1.70 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 765
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 36853.6 (10h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3732081
telemt_connections_bad_total 132369
telemt_connections_current 1209
telemt_connections_me_current 1209
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1546200
telemt_upstream_connect_attempt_total 23228
telemt_upstream_connect_success_total 23081
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 23221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7726
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_reconnect_attempts_total 45601
telemt_me_reconnect_success_total 899
telemt_me_reader_eof_total 572
telemt_me_idle_close_by_peer_total 572
telemt_me_route_drop_no_conn_total 1000549
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1810686
telemt_me_endpoint_quarantine_total 263
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 277
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10024
telemt_desync_full_logged_total 3441
telemt_desync_suppressed_total 6583
telemt_desync_frames_bucket_total{bucket="1_2"} 1772
telemt_desync_frames_bucket_total{bucket="3_10"} 3840
telemt_desync_frames_bucket_total{bucket="gt_10"} 4412
telemt_pool_swap_total 39
telemt_pool_force_close_total 1273
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 121
telemt_me_draining_writers_reap_progress_total 12636
telemt_me_writer_removed_unexpected_total 651
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1326
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11982
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1067
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11363
telemt_me_writer_teardown_success_total{mode="normal"} 13308
telemt_me_writer_teardown_noop_total 12638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25946
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.093982
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25946
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 121
telemt_me_refill_failed_total 2597
telemt_me_writer_restored_same_endpoint_total 807
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1814435
telemt_user_connections_current{user="hello"} 1209
telemt_user_octets_from_client{user="hello"} 52810490328 (49.18 GB)
telemt_user_octets_to_client{user="hello"} 775771032862 (722.49 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 621
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 17824.7 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165481
telemt_connections_bad_total 1401
telemt_connections_current 301
telemt_connections_me_current 301
telemt_handshake_timeouts_total 4224
telemt_upstream_connect_attempt_total 8203
telemt_upstream_connect_success_total 8183
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 8202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4597
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 168
telemt_me_reconnect_success_total 106
telemt_me_reader_eof_total 106
telemt_me_idle_close_by_peer_total 106
telemt_me_route_drop_no_conn_total 46583
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145527
telemt_me_endpoint_quarantine_total 161
telemt_me_single_endpoint_shadow_rotate_total 156
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 984
telemt_desync_full_logged_total 244
telemt_desync_suppressed_total 740
telemt_desync_frames_bucket_total{bucket="1_2"} 385
telemt_desync_frames_bucket_total{bucket="3_10"} 356
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 19
telemt_pool_force_close_total 442
telemt_me_writer_close_signal_drop_total 20
telemt_me_draining_writers_reap_progress_total 7366
telemt_me_writer_removed_unexpected_total 104
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 478
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6994
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 440
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6924
telemt_me_writer_teardown_success_total{mode="normal"} 7472
telemt_me_writer_teardown_noop_total 7366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 14688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 14810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 14828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 14838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 14838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 14838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 14838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 14838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 14838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 14838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 14838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 14838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 14838
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.809158
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 14838
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 20
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 98
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 145241
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 2736278732 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 85228188316 (79.37 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 100022.5 (27h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7076705
telemt_connections_bad_total 717647
telemt_connections_current 1680
telemt_connections_me_current 1680
telemt_handshake_timeouts_total 201371
telemt_upstream_connect_attempt_total 38418
telemt_upstream_connect_success_total 38271
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 38381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19230
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_reconnect_attempts_total 1503
telemt_me_reconnect_success_total 789
telemt_me_reader_eof_total 769
telemt_me_idle_close_by_peer_total 769
telemt_me_route_drop_no_conn_total 2101683
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5335795
telemt_me_endpoint_quarantine_total 691
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 765
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 20625
telemt_desync_full_logged_total 6887
telemt_desync_suppressed_total 13738
telemt_desync_frames_bucket_total{bucket="1_2"} 5018
telemt_desync_frames_bucket_total{bucket="3_10"} 7477
telemt_desync_frames_bucket_total{bucket="gt_10"} 8130
telemt_pool_swap_total 111
telemt_pool_force_close_total 2996
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 372
telemt_me_draining_writers_reap_progress_total 34564
telemt_me_writer_removed_unexpected_total 742
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2785
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32538
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2908
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31568
telemt_me_writer_teardown_success_total{mode="normal"} 35323
telemt_me_writer_teardown_noop_total 34566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69889
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.572592
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69889
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 372
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 704
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 5310977
telemt_user_connections_current{user="hello"} 1680
telemt_user_octets_from_client{user="hello"} 107992783096 (100.58 GB)
telemt_user_octets_to_client{user="hello"} 2495217901308 (2.27 TB)
telemt_user_unique_ips_current{user="hello"} 782
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 100019.0 (27h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6068764
telemt_connections_bad_total 596536
telemt_connections_current 1601
telemt_connections_me_current 1601
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 168314
telemt_upstream_connect_attempt_total 54319
telemt_upstream_connect_success_total 53903
telemt_upstream_connect_fail_total 357
telemt_upstream_connect_attempts_per_request{bucket="1"} 54260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20947
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 357
telemt_me_reconnect_attempts_total 5392
telemt_me_reconnect_success_total 1101
telemt_me_reader_eof_total 983
telemt_me_idle_close_by_peer_total 983
telemt_me_seq_mismatch_total 42
telemt_me_route_drop_no_conn_total 2155714
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4706849
telemt_me_endpoint_quarantine_total 797
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 761
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 19392
telemt_desync_full_logged_total 6518
telemt_desync_suppressed_total 12874
telemt_desync_frames_bucket_total{bucket="1_2"} 4875
telemt_desync_frames_bucket_total{bucket="3_10"} 7057
telemt_desync_frames_bucket_total{bucket="gt_10"} 7460
telemt_pool_swap_total 109
telemt_pool_force_close_total 2954
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 367
telemt_me_draining_writers_reap_progress_total 33233
telemt_me_writer_removed_unexpected_total 995
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3264
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31009
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2731
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30279
telemt_me_writer_teardown_success_total{mode="normal"} 34273
telemt_me_writer_teardown_noop_total 33237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67510
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.904087
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67510
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 367
telemt_me_refill_failed_total 248
telemt_me_writer_restored_same_endpoint_total 856
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 4710096
telemt_user_connections_current{user="hello"} 1601
telemt_user_octets_from_client{user="hello"} 88989150149 (82.88 GB)
telemt_user_octets_to_client{user="hello"} 2020134088132 (1.84 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 727
telemt_user_unique_ips_recent_window{user="hello"} 162
```