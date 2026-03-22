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

# Server Metrics 2026-03-22 01:49:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 17010.1 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 245044
telemt_connections_bad_total 17453
telemt_connections_current 659
telemt_connections_me_current 659
telemt_handshake_timeouts_total 14197
telemt_upstream_connect_attempt_total 7081
telemt_upstream_connect_success_total 7080
telemt_upstream_connect_attempts_per_request{bucket="1"} 7080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4492
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 239
telemt_me_reconnect_success_total 114
telemt_me_reader_eof_total 113
telemt_me_idle_close_by_peer_total 113
telemt_me_route_drop_no_conn_total 45549
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199905
telemt_me_endpoint_quarantine_total 133
telemt_me_single_endpoint_shadow_rotate_total 144
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
telemt_me_writers_active_current 46
telemt_desync_total 1776
telemt_desync_full_logged_total 486
telemt_desync_suppressed_total 1290
telemt_desync_frames_bucket_total{bucket="1_2"} 567
telemt_desync_frames_bucket_total{bucket="3_10"} 644
telemt_desync_frames_bucket_total{bucket="gt_10"} 565
telemt_pool_swap_total 18
telemt_pool_force_close_total 468
telemt_me_writer_close_signal_drop_total 33
telemt_me_draining_writers_reap_progress_total 6353
telemt_me_writer_removed_unexpected_total 113
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 442
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6014
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 463
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5885
telemt_me_writer_teardown_success_total{mode="normal"} 6456
telemt_me_writer_teardown_noop_total 6354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 12423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 12656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 12732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 12784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 12808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 12810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 12810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 12810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 12810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 12810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 12810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 12810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 12810
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.153192
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 12810
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 33
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 104
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 199594
telemt_user_connections_current{user="hello"} 659
telemt_user_octets_from_client{user="hello"} 2159322000 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 69333184392 (64.57 GB)
telemt_user_unique_ips_current{user="hello"} 331
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 30376.1 (8h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 749173
telemt_connections_bad_total 43234
telemt_connections_current 678
telemt_connections_me_current 678
telemt_handshake_timeouts_total 27857
telemt_upstream_connect_attempt_total 13889
telemt_upstream_connect_success_total 13668
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 13869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7597
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_reconnect_attempts_total 1162
telemt_me_reconnect_success_total 431
telemt_me_reader_eof_total 382
telemt_me_idle_close_by_peer_total 382
telemt_me_route_drop_no_conn_total 336253
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 598931
telemt_me_endpoint_quarantine_total 283
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 246
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 17
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
telemt_me_writers_active_current 46
telemt_desync_total 2629
telemt_desync_full_logged_total 1502
telemt_desync_suppressed_total 1127
telemt_desync_frames_bucket_total{bucket="1_2"} 560
telemt_desync_frames_bucket_total{bucket="3_10"} 995
telemt_desync_frames_bucket_total{bucket="gt_10"} 1074
telemt_pool_swap_total 32
telemt_pool_force_close_total 884
telemt_me_writer_close_signal_drop_total 61
telemt_me_draining_writers_reap_progress_total 12292
telemt_me_writer_removed_unexpected_total 363
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1043
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11618
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 862
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11408
telemt_me_writer_teardown_success_total{mode="normal"} 12661
telemt_me_writer_teardown_noop_total 12292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24953
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.505559
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24953
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 61
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 317
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 598051
telemt_user_connections_current{user="hello"} 678
telemt_user_octets_from_client{user="hello"} 9923891112 (9.24 GB)
telemt_user_octets_to_client{user="hello"} 214556001996 (199.82 GB)
telemt_user_unique_ips_current{user="hello"} 453
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 105236.1 (29h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7645748
telemt_connections_bad_total 620158
telemt_connections_current 1838
telemt_connections_me_current 1838
telemt_handshake_timeouts_total 250617
telemt_upstream_connect_attempt_total 38752
telemt_upstream_connect_success_total 38679
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 38686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20981
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1552
telemt_me_reconnect_success_total 788
telemt_me_reader_eof_total 799
telemt_me_idle_close_by_peer_total 799
telemt_me_route_drop_no_conn_total 4523934
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6202087
telemt_me_endpoint_quarantine_total 675
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 784
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 26239
telemt_desync_full_logged_total 8671
telemt_desync_suppressed_total 17568
telemt_desync_frames_bucket_total{bucket="1_2"} 5647
telemt_desync_frames_bucket_total{bucket="3_10"} 10235
telemt_desync_frames_bucket_total{bucket="gt_10"} 10357
telemt_pool_swap_total 113
telemt_pool_force_close_total 3784
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 596
telemt_me_draining_writers_reap_progress_total 35360
telemt_me_writer_removed_unexpected_total 768
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2953
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32719
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3545
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31576
telemt_me_writer_teardown_success_total{mode="normal"} 35672
telemt_me_writer_teardown_noop_total 35404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71076
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 157.423980
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71076
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 596
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 704
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 6194326
telemt_user_connections_current{user="hello"} 1838
telemt_user_octets_from_client{user="hello"} 105711296112 (98.45 GB)
telemt_user_octets_to_client{user="hello"} 2054720847116 (1.87 TB)
telemt_user_unique_ips_current{user="hello"} 890
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 105237.4 (29h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6301664
telemt_connections_bad_total 584371
telemt_connections_current 1392
telemt_connections_me_current 1392
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 208916
telemt_upstream_connect_attempt_total 42766
telemt_upstream_connect_success_total 42381
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 42569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20710
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1907
telemt_me_reconnect_success_total 854
telemt_me_reader_eof_total 824
telemt_me_idle_close_by_peer_total 824
telemt_me_route_drop_no_conn_total 2245995
telemt_me_route_drop_channel_closed_total 257
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4721364
telemt_me_endpoint_quarantine_total 651
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 807
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 22424
telemt_desync_full_logged_total 7617
telemt_desync_suppressed_total 14807
telemt_desync_frames_bucket_total{bucket="1_2"} 5405
telemt_desync_frames_bucket_total{bucket="3_10"} 8701
telemt_desync_frames_bucket_total{bucket="gt_10"} 8318
telemt_pool_swap_total 114
telemt_pool_force_close_total 3419
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 357
telemt_me_draining_writers_reap_progress_total 33883
telemt_me_writer_removed_unexpected_total 809
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2863
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31766
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3206
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30464
telemt_me_writer_teardown_success_total{mode="normal"} 34629
telemt_me_writer_teardown_noop_total 33889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68518
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.229156
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68518
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 357
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 746
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 4643622
telemt_user_connections_current{user="hello"} 1392
telemt_user_octets_from_client{user="hello"} 139618333461 (130.03 GB)
telemt_user_octets_to_client{user="hello"} 2185410768999 (1.99 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 714
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 105201.3 (29h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6189827
telemt_connections_bad_total 545396
telemt_connections_current 1359
telemt_connections_me_current 1359
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 199088
telemt_upstream_connect_attempt_total 49069
telemt_upstream_connect_success_total 48717
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 48853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22097
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 423
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1060
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1951
telemt_me_reconnect_success_total 877
telemt_me_reader_eof_total 821
telemt_me_idle_close_by_peer_total 821
telemt_me_route_drop_no_conn_total 2138761
telemt_me_route_drop_channel_closed_total 117
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4615109
telemt_me_endpoint_quarantine_total 730
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 787
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_me_writers_active_current 46
telemt_desync_total 22248
telemt_desync_full_logged_total 7458
telemt_desync_suppressed_total 14790
telemt_desync_frames_bucket_total{bucket="1_2"} 5440
telemt_desync_frames_bucket_total{bucket="3_10"} 8523
telemt_desync_frames_bucket_total{bucket="gt_10"} 8285
telemt_pool_swap_total 113
telemt_pool_force_close_total 3291
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 379
telemt_me_draining_writers_reap_progress_total 35244
telemt_me_writer_removed_unexpected_total 794
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2914
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33137
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3076
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31953
telemt_me_writer_teardown_success_total{mode="normal"} 36051
telemt_me_writer_teardown_noop_total 35255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71306
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.751485
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71306
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 379
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 761
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 4610824
telemt_user_connections_current{user="hello"} 1359
telemt_user_octets_from_client{user="hello"} 133016422023 (123.88 GB)
telemt_user_octets_to_client{user="hello"} 2106195391899 (1.92 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 668
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 105240.7 (29h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20271765
telemt_connections_bad_total 1574484
telemt_connections_current 2001
telemt_connections_me_current 2001
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 596087
telemt_upstream_connect_attempt_total 194115
telemt_upstream_connect_success_total 176190
telemt_upstream_connect_fail_total 16220
telemt_upstream_connect_attempts_per_request{bucket="1"} 192410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 124328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41730
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8911
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16220
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64774
telemt_me_reconnect_success_total 2277
telemt_me_reader_eof_total 1415
telemt_me_idle_close_by_peer_total 1414
telemt_me_route_drop_no_conn_total 39489776
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16423545
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 816
telemt_me_single_endpoint_outage_enter_total 133
telemt_me_single_endpoint_outage_exit_total 133
telemt_me_single_endpoint_outage_reconnect_attempt_total 283
telemt_me_single_endpoint_outage_reconnect_success_total 68
telemt_me_single_endpoint_quarantine_bypass_total 283
telemt_me_single_endpoint_shadow_rotate_total 823
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 62
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
telemt_desync_total 31834
telemt_desync_full_logged_total 9518
telemt_desync_suppressed_total 22316
telemt_desync_frames_bucket_total{bucket="1_2"} 6896
telemt_desync_frames_bucket_total{bucket="3_10"} 14127
telemt_desync_frames_bucket_total{bucket="gt_10"} 10811
telemt_pool_swap_total 108
telemt_pool_force_close_total 3548
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 788
telemt_me_draining_writers_reap_progress_total 32793
telemt_me_writer_removed_unexpected_total 2117
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4450
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30197
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3025
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 523
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29245
telemt_me_writer_teardown_success_total{mode="normal"} 34647
telemt_me_writer_teardown_noop_total 32819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67466
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 213.706707
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67466
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 788
telemt_me_refill_failed_total 3799
telemt_me_writer_restored_same_endpoint_total 1560
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 536
telemt_user_connections_total{user="hello"} 16553132
telemt_user_connections_current{user="hello"} 2001
telemt_user_octets_from_client{user="hello"} 207739443250 (193.47 GB)
telemt_user_octets_to_client{user="hello"} 1173723393015 (1.07 TB)
telemt_user_msgs_from_client{user="hello"} 373576
telemt_user_msgs_to_client{user="hello"} 663916
telemt_user_unique_ips_current{user="hello"} 977
telemt_user_unique_ips_recent_window{user="hello"} 206
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 105208.0 (29h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5953451
telemt_connections_bad_total 558369
telemt_connections_current 1473
telemt_connections_me_current 1473
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 124317
telemt_upstream_connect_attempt_total 57454
telemt_upstream_connect_success_total 56784
telemt_upstream_connect_fail_total 573
telemt_upstream_connect_attempts_per_request{bucket="1"} 57357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23073
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 347
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 573
telemt_me_reconnect_attempts_total 69588
telemt_me_reconnect_success_total 1760
telemt_me_reader_eof_total 1535
telemt_me_idle_close_by_peer_total 1534
telemt_me_route_drop_no_conn_total 2378600
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4645830
telemt_me_endpoint_quarantine_total 711
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 793
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_me_writers_active_current 45
telemt_desync_total 23244
telemt_desync_full_logged_total 8168
telemt_desync_suppressed_total 15076
telemt_desync_frames_bucket_total{bucket="1_2"} 4417
telemt_desync_frames_bucket_total{bucket="3_10"} 8996
telemt_desync_frames_bucket_total{bucket="gt_10"} 9831
telemt_pool_swap_total 108
telemt_pool_force_close_total 3135
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 389
telemt_me_draining_writers_reap_progress_total 36819
telemt_me_writer_removed_unexpected_total 1576
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3816
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34607
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2734
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33684
telemt_me_writer_teardown_success_total{mode="normal"} 38423
telemt_me_writer_teardown_noop_total 36820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75243
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.096303
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75243
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 389
telemt_me_refill_failed_total 4204
telemt_me_writer_restored_same_endpoint_total 1474
telemt_me_writer_restored_fallback_total 32
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 4638777
telemt_user_connections_current{user="hello"} 1473
telemt_user_octets_from_client{user="hello"} 123505167396 (115.02 GB)
telemt_user_octets_to_client{user="hello"} 1895827978946 (1.72 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 724
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 42043.9 (11h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3845566
telemt_connections_bad_total 139402
telemt_connections_current 1137
telemt_connections_me_current 1137
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1577135
telemt_upstream_connect_attempt_total 25876
telemt_upstream_connect_success_total 25707
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 25869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9126
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_reconnect_attempts_total 45780
telemt_me_reconnect_success_total 944
telemt_me_reader_eof_total 622
telemt_me_idle_close_by_peer_total 622
telemt_me_route_drop_no_conn_total 1013193
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1878914
telemt_me_endpoint_quarantine_total 312
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 321
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10299
telemt_desync_full_logged_total 3550
telemt_desync_suppressed_total 6749
telemt_desync_frames_bucket_total{bucket="1_2"} 1832
telemt_desync_frames_bucket_total{bucket="3_10"} 3955
telemt_desync_frames_bucket_total{bucket="gt_10"} 4512
telemt_pool_swap_total 45
telemt_pool_force_close_total 1408
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 131
telemt_me_draining_writers_reap_progress_total 15054
telemt_me_writer_removed_unexpected_total 699
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1452
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14324
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1202
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13646
telemt_me_writer_teardown_success_total{mode="normal"} 15776
telemt_me_writer_teardown_noop_total 15056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30832
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.338217
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30832
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 131
telemt_me_refill_failed_total 2605
telemt_me_writer_restored_same_endpoint_total 845
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1882595
telemt_user_connections_current{user="hello"} 1137
telemt_user_octets_from_client{user="hello"} 53539284704 (49.86 GB)
telemt_user_octets_to_client{user="hello"} 802487644290 (747.37 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 626
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 23015.1 (6h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184548
telemt_connections_bad_total 1620
telemt_connections_current 304
telemt_connections_me_current 304
telemt_handshake_timeouts_total 5107
telemt_upstream_connect_attempt_total 10995
telemt_upstream_connect_success_total 10970
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 10993
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6244
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 228
telemt_me_reconnect_success_total 142
telemt_me_reader_eof_total 145
telemt_me_idle_close_by_peer_total 145
telemt_me_route_drop_no_conn_total 50500
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162412
telemt_me_endpoint_quarantine_total 231
telemt_me_single_endpoint_shadow_rotate_total 203
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
telemt_desync_total 1008
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 754
telemt_desync_frames_bucket_total{bucket="1_2"} 389
telemt_desync_frames_bucket_total{bucket="3_10"} 369
telemt_desync_frames_bucket_total{bucket="gt_10"} 250
telemt_pool_swap_total 25
telemt_pool_force_close_total 559
telemt_me_writer_close_signal_drop_total 22
telemt_me_draining_writers_reap_progress_total 9917
telemt_me_writer_removed_unexpected_total 140
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 651
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9411
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 557
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9358
telemt_me_writer_teardown_success_total{mode="normal"} 10062
telemt_me_writer_teardown_noop_total 9917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 19784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 19951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 19969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 19979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 19979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 19979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 19979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 19979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 19979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 19979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 19979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 19979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 19979
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.947324
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 19979
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 22
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 131
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 162111
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 2966307216 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 93852654724 (87.41 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 105212.5 (29h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7231432
telemt_connections_bad_total 736633
telemt_connections_current 1553
telemt_connections_me_current 1553
telemt_handshake_timeouts_total 206060
telemt_upstream_connect_attempt_total 40967
telemt_upstream_connect_success_total 40813
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 40930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20553
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_reconnect_attempts_total 1545
telemt_me_reconnect_success_total 828
telemt_me_reader_eof_total 810
telemt_me_idle_close_by_peer_total 810
telemt_me_route_drop_no_conn_total 2116090
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5424773
telemt_me_endpoint_quarantine_total 727
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 808
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_me_writers_active_current 47
telemt_desync_total 21329
telemt_desync_full_logged_total 6996
telemt_desync_suppressed_total 14333
telemt_desync_frames_bucket_total{bucket="1_2"} 5359
telemt_desync_frames_bucket_total{bucket="3_10"} 7721
telemt_desync_frames_bucket_total{bucket="gt_10"} 8249
telemt_pool_swap_total 116
telemt_pool_force_close_total 3128
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 380
telemt_me_draining_writers_reap_progress_total 36923
telemt_me_writer_removed_unexpected_total 781
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2920
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34803
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3040
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33795
telemt_me_writer_teardown_success_total{mode="normal"} 37723
telemt_me_writer_teardown_noop_total 36925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74648
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.614817
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74648
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 380
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 738
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 5399820
telemt_user_connections_current{user="hello"} 1553
telemt_user_octets_from_client{user="hello"} 108669211608 (101.21 GB)
telemt_user_octets_to_client{user="hello"} 2521175951520 (2.29 TB)
telemt_user_unique_ips_current{user="hello"} 708
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 105208.9 (29h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6229348
telemt_connections_bad_total 614513
telemt_connections_current 1426
telemt_connections_me_current 1426
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 171035
telemt_upstream_connect_attempt_total 56735
telemt_upstream_connect_success_total 56313
telemt_upstream_connect_fail_total 363
telemt_upstream_connect_attempts_per_request{bucket="1"} 56676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22200
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 363
telemt_me_reconnect_attempts_total 5506
telemt_me_reconnect_success_total 1141
telemt_me_reader_eof_total 1023
telemt_me_idle_close_by_peer_total 1023
telemt_me_seq_mismatch_total 45
telemt_me_route_drop_no_conn_total 2169677
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4793012
telemt_me_endpoint_quarantine_total 834
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 803
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 19970
telemt_desync_full_logged_total 6629
telemt_desync_suppressed_total 13341
telemt_desync_frames_bucket_total{bucket="1_2"} 5099
telemt_desync_frames_bucket_total{bucket="3_10"} 7273
telemt_desync_frames_bucket_total{bucket="gt_10"} 7598
telemt_pool_swap_total 114
telemt_pool_force_close_total 3085
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 375
telemt_me_draining_writers_reap_progress_total 35473
telemt_me_writer_removed_unexpected_total 1035
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3434
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33122
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2862
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32388
telemt_me_writer_teardown_success_total{mode="normal"} 36556
telemt_me_writer_teardown_noop_total 35477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72033
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.992764
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72033
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 375
telemt_me_refill_failed_total 252
telemt_me_writer_restored_same_endpoint_total 889
telemt_me_writer_restored_fallback_total 58
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 4796128
telemt_user_connections_current{user="hello"} 1426
telemt_user_octets_from_client{user="hello"} 90026048181 (83.84 GB)
telemt_user_octets_to_client{user="hello"} 2051009967040 (1.87 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 689
telemt_user_unique_ips_recent_window{user="hello"} 112
```