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

# Server Metrics 2026-03-22 01:24:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 15482.6 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225766
telemt_connections_bad_total 15962
telemt_connections_current 497
telemt_connections_me_current 497
telemt_handshake_timeouts_total 13045
telemt_upstream_connect_attempt_total 6475
telemt_upstream_connect_success_total 6474
telemt_upstream_connect_attempts_per_request{bucket="1"} 6474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4085
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 215
telemt_me_reconnect_success_total 107
telemt_me_reader_eof_total 103
telemt_me_idle_close_by_peer_total 103
telemt_me_route_drop_no_conn_total 42655
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 184199
telemt_me_endpoint_quarantine_total 122
telemt_me_single_endpoint_shadow_rotate_total 135
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
telemt_me_writers_active_current 44
telemt_desync_total 1563
telemt_desync_full_logged_total 432
telemt_desync_suppressed_total 1131
telemt_desync_frames_bucket_total{bucket="1_2"} 481
telemt_desync_frames_bucket_total{bucket="3_10"} 566
telemt_desync_frames_bucket_total{bucket="gt_10"} 516
telemt_pool_swap_total 17
telemt_pool_force_close_total 444
telemt_me_writer_close_signal_drop_total 30
telemt_me_draining_writers_reap_progress_total 5801
telemt_me_writer_removed_unexpected_total 105
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 420
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5474
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5357
telemt_me_writer_teardown_success_total{mode="normal"} 5894
telemt_me_writer_teardown_noop_total 5802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 11356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 11558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 11694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 11696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 11696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 11696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 11696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 11696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 11696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 11696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 11696
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.897206
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 11696
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 30
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 97
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 183883
telemt_user_connections_current{user="hello"} 497
telemt_user_octets_from_client{user="hello"} 2015086476 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 61981139848 (57.72 GB)
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 28848.9 (8h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 732295
telemt_connections_bad_total 42204
telemt_connections_current 804
telemt_connections_me_current 804
telemt_handshake_timeouts_total 27412
telemt_upstream_connect_attempt_total 12729
telemt_upstream_connect_success_total 12523
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 12709
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5582
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6901
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_reconnect_attempts_total 1088
telemt_me_reconnect_success_total 367
telemt_me_reader_eof_total 319
telemt_me_idle_close_by_peer_total 319
telemt_me_route_drop_no_conn_total 334120
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 587604
telemt_me_endpoint_quarantine_total 263
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 231
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 12
telemt_desync_total 2569
telemt_desync_full_logged_total 1472
telemt_desync_suppressed_total 1097
telemt_desync_frames_bucket_total{bucket="1_2"} 551
telemt_desync_frames_bucket_total{bucket="3_10"} 963
telemt_desync_frames_bucket_total{bucket="gt_10"} 1055
telemt_pool_swap_total 31
telemt_pool_force_close_total 843
telemt_me_writer_close_signal_drop_total 61
telemt_me_draining_writers_reap_progress_total 11244
telemt_me_writer_removed_unexpected_total 301
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 942
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10608
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 836
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10401
telemt_me_writer_teardown_success_total{mode="normal"} 11550
telemt_me_writer_teardown_noop_total 11244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 22319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 22600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 22688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 22780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 22792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 22794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 22794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 22794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 22794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 22794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 22794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 22794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 22794
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.472494
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 22794
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 61
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 257
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 586737
telemt_user_connections_current{user="hello"} 804
telemt_user_octets_from_client{user="hello"} 9831239864 (9.16 GB)
telemt_user_octets_to_client{user="hello"} 210078939824 (195.65 GB)
telemt_user_unique_ips_current{user="hello"} 523
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 103709.0 (28h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7603461
telemt_connections_bad_total 617646
telemt_connections_current 1053
telemt_connections_me_current 1053
telemt_handshake_timeouts_total 248511
telemt_upstream_connect_attempt_total 38073
telemt_upstream_connect_success_total 38000
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 38007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20619
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 163
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1546
telemt_me_reconnect_success_total 782
telemt_me_reader_eof_total 794
telemt_me_idle_close_by_peer_total 794
telemt_me_route_drop_no_conn_total 4518693
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6174979
telemt_me_endpoint_quarantine_total 664
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 774
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
telemt_desync_total 26180
telemt_desync_full_logged_total 8649
telemt_desync_suppressed_total 17531
telemt_desync_frames_bucket_total{bucket="1_2"} 5635
telemt_desync_frames_bucket_total{bucket="3_10"} 10210
telemt_desync_frames_bucket_total{bucket="gt_10"} 10335
telemt_pool_swap_total 112
telemt_pool_force_close_total 3760
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 593
telemt_me_draining_writers_reap_progress_total 34731
telemt_me_writer_removed_unexpected_total 763
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2919
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32119
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3521
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30971
telemt_me_writer_teardown_success_total{mode="normal"} 35038
telemt_me_writer_teardown_noop_total 34775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69813
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 156.939630
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69813
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 593
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 699
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 6167230
telemt_user_connections_current{user="hello"} 1053
telemt_user_octets_from_client{user="hello"} 105479714868 (98.24 GB)
telemt_user_octets_to_client{user="hello"} 2043729410756 (1.86 TB)
telemt_user_unique_ips_current{user="hello"} 547
telemt_user_unique_ips_recent_window{user="hello"} 487
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 103710.3 (28h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6257672
telemt_connections_bad_total 583266
telemt_connections_current 893
telemt_connections_me_current 893
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 208163
telemt_upstream_connect_attempt_total 42177
telemt_upstream_connect_success_total 41792
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 41980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20402
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1902
telemt_me_reconnect_success_total 849
telemt_me_reader_eof_total 818
telemt_me_idle_close_by_peer_total 818
telemt_me_route_drop_no_conn_total 2226701
telemt_me_route_drop_channel_closed_total 257
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4690134
telemt_me_endpoint_quarantine_total 644
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 795
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
telemt_desync_total 22352
telemt_desync_full_logged_total 7592
telemt_desync_suppressed_total 14760
telemt_desync_frames_bucket_total{bucket="1_2"} 5380
telemt_desync_frames_bucket_total{bucket="3_10"} 8674
telemt_desync_frames_bucket_total{bucket="gt_10"} 8298
telemt_pool_swap_total 113
telemt_pool_force_close_total 3393
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 355
telemt_me_draining_writers_reap_progress_total 33346
telemt_me_writer_removed_unexpected_total 804
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2838
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31248
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3180
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29953
telemt_me_writer_teardown_success_total{mode="normal"} 34086
telemt_me_writer_teardown_noop_total 33352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67438
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.216266
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67438
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 355
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 741
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 4619732
telemt_user_connections_current{user="hello"} 893
telemt_user_octets_from_client{user="hello"} 139345173889 (129.78 GB)
telemt_user_octets_to_client{user="hello"} 2170855117731 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 451
telemt_user_unique_ips_recent_window{user="hello"} 392
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 103674.1 (28h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6153984
telemt_connections_bad_total 544840
telemt_connections_current 1735
telemt_connections_me_current 1735
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 196882
telemt_upstream_connect_attempt_total 48437
telemt_upstream_connect_success_total 48099
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 48235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21736
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 411
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1058
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1940
telemt_me_reconnect_success_total 868
telemt_me_reader_eof_total 812
telemt_me_idle_close_by_peer_total 812
telemt_me_route_drop_no_conn_total 2123715
telemt_me_route_drop_channel_closed_total 114
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4586309
telemt_me_endpoint_quarantine_total 722
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 776
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
telemt_me_writers_active_current 43
telemt_desync_total 22144
telemt_desync_full_logged_total 7414
telemt_desync_suppressed_total 14730
telemt_desync_frames_bucket_total{bucket="1_2"} 5411
telemt_desync_frames_bucket_total{bucket="3_10"} 8483
telemt_desync_frames_bucket_total{bucket="gt_10"} 8250
telemt_pool_swap_total 112
telemt_pool_force_close_total 3246
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 379
telemt_me_draining_writers_reap_progress_total 34667
telemt_me_writer_removed_unexpected_total 785
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2882
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32583
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3031
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31421
telemt_me_writer_teardown_success_total{mode="normal"} 35465
telemt_me_writer_teardown_noop_total 34678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70143
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.706352
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70143
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 379
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 752
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 4586980
telemt_user_connections_current{user="hello"} 1735
telemt_user_octets_from_client{user="hello"} 132771580363 (123.65 GB)
telemt_user_octets_to_client{user="hello"} 2095562341651 (1.91 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 829
telemt_user_unique_ips_recent_window{user="hello"} 313
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 103713.0 (28h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20207569
telemt_connections_bad_total 1551817
telemt_connections_current 1698
telemt_connections_me_current 1698
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 592381
telemt_upstream_connect_attempt_total 191239
telemt_upstream_connect_success_total 173527
telemt_upstream_connect_fail_total 16055
telemt_upstream_connect_attempts_per_request{bucket="1"} 189582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 122249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41166
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8891
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16055
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64609
telemt_me_reconnect_success_total 2221
telemt_me_reader_eof_total 1403
telemt_me_idle_close_by_peer_total 1402
telemt_me_route_drop_no_conn_total 39482900
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16389586
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 804
telemt_me_single_endpoint_outage_enter_total 125
telemt_me_single_endpoint_outage_exit_total 125
telemt_me_single_endpoint_outage_reconnect_attempt_total 261
telemt_me_single_endpoint_outage_reconnect_success_total 64
telemt_me_single_endpoint_quarantine_bypass_total 261
telemt_me_single_endpoint_shadow_rotate_total 809
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
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
telemt_desync_total 31721
telemt_desync_full_logged_total 9479
telemt_desync_suppressed_total 22242
telemt_desync_frames_bucket_total{bucket="1_2"} 6881
telemt_desync_frames_bucket_total{bucket="3_10"} 14077
telemt_desync_frames_bucket_total{bucket="gt_10"} 10763
telemt_pool_swap_total 107
telemt_pool_force_close_total 3522
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 778
telemt_me_draining_writers_reap_progress_total 32317
telemt_me_writer_removed_unexpected_total 2062
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4367
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29748
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2999
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 523
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28795
telemt_me_writer_teardown_success_total{mode="normal"} 34115
telemt_me_writer_teardown_noop_total 32343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66458
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 213.637499
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66458
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 778
telemt_me_refill_failed_total 3799
telemt_me_writer_restored_same_endpoint_total 1539
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 502
telemt_user_connections_total{user="hello"} 16517109
telemt_user_connections_current{user="hello"} 1698
telemt_user_octets_from_client{user="hello"} 203165015632 (189.21 GB)
telemt_user_octets_to_client{user="hello"} 1163370138522 (1.06 TB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 764
telemt_user_unique_ips_recent_window{user="hello"} 705
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 103680.7 (28h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5925803
telemt_connections_bad_total 556748
telemt_connections_current 1394
telemt_connections_me_current 1394
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 123431
telemt_upstream_connect_attempt_total 56742
telemt_upstream_connect_success_total 56077
telemt_upstream_connect_fail_total 571
telemt_upstream_connect_attempts_per_request{bucket="1"} 56648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22688
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 344
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 571
telemt_me_reconnect_attempts_total 69546
telemt_me_reconnect_success_total 1747
telemt_me_reader_eof_total 1522
telemt_me_idle_close_by_peer_total 1521
telemt_me_route_drop_no_conn_total 2374868
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4622887
telemt_me_endpoint_quarantine_total 703
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 779
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_me_writers_active_current 41
telemt_desync_total 23203
telemt_desync_full_logged_total 8145
telemt_desync_suppressed_total 15058
telemt_desync_frames_bucket_total{bucket="1_2"} 4405
telemt_desync_frames_bucket_total{bucket="3_10"} 8978
telemt_desync_frames_bucket_total{bucket="gt_10"} 9820
telemt_pool_swap_total 107
telemt_pool_force_close_total 3089
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 387
telemt_me_draining_writers_reap_progress_total 36154
telemt_me_writer_removed_unexpected_total 1565
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3781
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33964
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2688
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33065
telemt_me_writer_teardown_success_total{mode="normal"} 37745
telemt_me_writer_teardown_noop_total 36155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73900
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.084032
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73900
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 387
telemt_me_refill_failed_total 4202
telemt_me_writer_restored_same_endpoint_total 1465
telemt_me_writer_restored_fallback_total 32
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 4615896
telemt_user_connections_current{user="hello"} 1394
telemt_user_octets_from_client{user="hello"} 123113106380 (114.66 GB)
telemt_user_octets_to_client{user="hello"} 1886649333314 (1.72 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 702
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 40516.3 (11h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3815757
telemt_connections_bad_total 138418
telemt_connections_current 1144
telemt_connections_me_current 1144
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1570866
telemt_upstream_connect_attempt_total 25019
telemt_upstream_connect_success_total 24855
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 25012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8677
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_reconnect_attempts_total 45763
telemt_me_reconnect_success_total 927
telemt_me_reader_eof_total 605
telemt_me_idle_close_by_peer_total 605
telemt_me_route_drop_no_conn_total 1009759
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1858655
telemt_me_endpoint_quarantine_total 299
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 306
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10189
telemt_desync_full_logged_total 3514
telemt_desync_suppressed_total 6675
telemt_desync_frames_bucket_total{bucket="1_2"} 1819
telemt_desync_frames_bucket_total{bucket="3_10"} 3897
telemt_desync_frames_bucket_total{bucket="gt_10"} 4473
telemt_pool_swap_total 43
telemt_pool_force_close_total 1372
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 128
telemt_me_draining_writers_reap_progress_total 14266
telemt_me_writer_removed_unexpected_total 683
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1411
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13560
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1166
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12894
telemt_me_writer_teardown_success_total{mode="normal"} 14971
telemt_me_writer_teardown_noop_total 14268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29239
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.312129
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29239
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 128
telemt_me_refill_failed_total 2605
telemt_me_writer_restored_same_endpoint_total 829
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1862353
telemt_user_connections_current{user="hello"} 1144
telemt_user_octets_from_client{user="hello"} 53405172328 (49.74 GB)
telemt_user_octets_to_client{user="hello"} 796141971774 (741.46 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 636
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 21487.2 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 178541
telemt_connections_bad_total 1541
telemt_connections_current 310
telemt_connections_me_current 310
telemt_handshake_timeouts_total 4935
telemt_upstream_connect_attempt_total 10217
telemt_upstream_connect_success_total 10193
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 10215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5785
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 223
telemt_me_reconnect_success_total 137
telemt_me_reader_eof_total 139
telemt_me_idle_close_by_peer_total 139
telemt_me_route_drop_no_conn_total 49276
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156929
telemt_me_endpoint_quarantine_total 211
telemt_me_single_endpoint_shadow_rotate_total 188
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 996
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 747
telemt_desync_frames_bucket_total{bucket="1_2"} 388
telemt_desync_frames_bucket_total{bucket="3_10"} 364
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 23
telemt_pool_force_close_total 515
telemt_me_writer_close_signal_drop_total 20
telemt_me_draining_writers_reap_progress_total 9190
telemt_me_writer_removed_unexpected_total 135
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 612
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8717
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 513
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8675
telemt_me_writer_teardown_success_total{mode="normal"} 9329
telemt_me_writer_teardown_noop_total 9190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 18348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 18491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 18509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 18519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 18519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 18519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 18519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 18519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 18519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 18519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 18519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 18519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 18519
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.889529
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 18519
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 20
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 126
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 156636
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 2891266496 (2.69 GB)
telemt_user_octets_to_client{user="hello"} 91726500328 (85.43 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 103685.3 (28h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7180344
telemt_connections_bad_total 730827
telemt_connections_current 1813
telemt_connections_me_current 1813
telemt_handshake_timeouts_total 204831
telemt_upstream_connect_attempt_total 40254
telemt_upstream_connect_success_total 40100
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 40217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20182
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_reconnect_attempts_total 1538
telemt_me_reconnect_success_total 821
telemt_me_reader_eof_total 803
telemt_me_idle_close_by_peer_total 803
telemt_me_route_drop_no_conn_total 2112079
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5399332
telemt_me_endpoint_quarantine_total 722
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 796
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 21114
telemt_desync_full_logged_total 6970
telemt_desync_suppressed_total 14144
telemt_desync_frames_bucket_total{bucket="1_2"} 5243
telemt_desync_frames_bucket_total{bucket="3_10"} 7642
telemt_desync_frames_bucket_total{bucket="gt_10"} 8229
telemt_pool_swap_total 115
telemt_pool_force_close_total 3087
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 377
telemt_me_draining_writers_reap_progress_total 36240
telemt_me_writer_removed_unexpected_total 774
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2888
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34145
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2999
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33153
telemt_me_writer_teardown_success_total{mode="normal"} 37033
telemt_me_writer_teardown_noop_total 36242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73275
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.598100
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73275
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 377
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 731
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 5374421
telemt_user_connections_current{user="hello"} 1813
telemt_user_octets_from_client{user="hello"} 108443381048 (101.00 GB)
telemt_user_octets_to_client{user="hello"} 2513456340648 (2.29 TB)
telemt_user_unique_ips_current{user="hello"} 811
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 103681.7 (28h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6187406
telemt_connections_bad_total 610507
telemt_connections_current 1381
telemt_connections_me_current 1381
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 170070
telemt_upstream_connect_attempt_total 56062
telemt_upstream_connect_success_total 55641
telemt_upstream_connect_fail_total 362
telemt_upstream_connect_attempts_per_request{bucket="1"} 56003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21831
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 362
telemt_me_reconnect_attempts_total 5498
telemt_me_reconnect_success_total 1135
telemt_me_reader_eof_total 1017
telemt_me_idle_close_by_peer_total 1017
telemt_me_seq_mismatch_total 45
telemt_me_route_drop_no_conn_total 2166013
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4768362
telemt_me_endpoint_quarantine_total 831
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 792
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
telemt_me_writers_active_current 44
telemt_desync_total 19753
telemt_desync_full_logged_total 6604
telemt_desync_suppressed_total 13149
telemt_desync_frames_bucket_total{bucket="1_2"} 4984
telemt_desync_frames_bucket_total{bucket="3_10"} 7187
telemt_desync_frames_bucket_total{bucket="gt_10"} 7582
telemt_pool_swap_total 113
telemt_pool_force_close_total 3044
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 373
telemt_me_draining_writers_reap_progress_total 34838
telemt_me_writer_removed_unexpected_total 1029
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3398
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32517
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2821
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31794
telemt_me_writer_teardown_success_total{mode="normal"} 35915
telemt_me_writer_teardown_noop_total 34842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70757
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.981894
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70757
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 373
telemt_me_refill_failed_total 252
telemt_me_writer_restored_same_endpoint_total 883
telemt_me_writer_restored_fallback_total 58
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 4771504
telemt_user_connections_current{user="hello"} 1381
telemt_user_octets_from_client{user="hello"} 89803776973 (83.64 GB)
telemt_user_octets_to_client{user="hello"} 2042367888376 (1.86 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 662
telemt_user_unique_ips_recent_window{user="hello"} 125
```