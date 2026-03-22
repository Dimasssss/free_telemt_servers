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

# Server Metrics 2026-03-22 22:33:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 91612.9 (25h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3322042
telemt_connections_bad_total 257357
telemt_connections_current 932
telemt_connections_me_current 932
telemt_handshake_timeouts_total 105007
telemt_upstream_connect_attempt_total 33703
telemt_upstream_connect_success_total 33702
telemt_upstream_connect_attempts_per_request{bucket="1"} 33702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21978
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1345
telemt_me_reconnect_success_total 555
telemt_me_reader_eof_total 571
telemt_me_idle_close_by_peer_total 571
telemt_me_route_drop_no_conn_total 2961691
telemt_me_route_drop_channel_closed_total 1227
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2785825
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 624
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 713
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 11933
telemt_desync_full_logged_total 3739
telemt_desync_suppressed_total 8194
telemt_desync_frames_bucket_total{bucket="1_2"} 3225
telemt_desync_frames_bucket_total{bucket="3_10"} 4363
telemt_desync_frames_bucket_total{bucket="gt_10"} 4345
telemt_pool_swap_total 101
telemt_pool_force_close_total 3146
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 629
telemt_me_draining_writers_reap_progress_total 30837
telemt_me_writer_removed_unexpected_total 551
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2234
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28822
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3091
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27691
telemt_me_writer_teardown_success_total{mode="normal"} 31056
telemt_me_writer_teardown_noop_total 30848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61904
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 373.547511
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61904
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 629
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 494
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2775174
telemt_user_connections_current{user="hello"} 932
telemt_user_octets_from_client{user="hello"} 39830979016 (37.10 GB)
telemt_user_octets_to_client{user="hello"} 751944864052 (700.30 GB)
telemt_user_unique_ips_current{user="hello"} 370
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 104979.1 (29h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3947421
telemt_connections_bad_total 359042
telemt_connections_current 411
telemt_connections_me_current 411
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 99724
telemt_upstream_connect_attempt_total 63336
telemt_upstream_connect_success_total 62558
telemt_upstream_connect_fail_total 688
telemt_upstream_connect_attempts_per_request{bucket="1"} 63246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34496
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27862
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 200
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 688
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9432
telemt_me_reconnect_success_total 3453
telemt_me_reader_eof_total 3470
telemt_me_idle_close_by_peer_total 3470
telemt_me_route_drop_no_conn_total 3634697
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3139815
telemt_me_endpoint_quarantine_total 780
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 811
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
telemt_me_writers_active_current 44
telemt_desync_total 12789
telemt_desync_full_logged_total 7164
telemt_desync_suppressed_total 5625
telemt_desync_frames_bucket_total{bucket="1_2"} 2889
telemt_desync_frames_bucket_total{bucket="3_10"} 5018
telemt_desync_frames_bucket_total{bucket="gt_10"} 4882
telemt_pool_swap_total 96
telemt_pool_force_close_total 2936
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 241
telemt_me_draining_writers_reap_progress_total 42136
telemt_me_writer_removed_unexpected_total 3406
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5792
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39777
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2478
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39200
telemt_me_writer_teardown_success_total{mode="normal"} 45569
telemt_me_writer_teardown_noop_total 42137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87706
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.501349
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87706
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 241
telemt_me_refill_failed_total 226
telemt_me_writer_restored_same_endpoint_total 3123
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 3150471
telemt_user_connections_current{user="hello"} 411
telemt_user_octets_from_client{user="hello"} 42636273083 (39.71 GB)
telemt_user_octets_to_client{user="hello"} 777133688914 (723.76 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 179838.9 (49h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16199720
telemt_connections_bad_total 1606842
telemt_connections_current 1096
telemt_connections_me_current 1096
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 396031
telemt_upstream_connect_attempt_total 79834
telemt_upstream_connect_success_total 79734
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 79751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38550
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1701
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2893
telemt_me_reconnect_success_total 1505
telemt_me_reader_eof_total 1451
telemt_me_idle_close_by_peer_total 1449
telemt_me_route_drop_no_conn_total 14029065
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12885298
telemt_me_endpoint_quarantine_total 1161
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1344
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 53280
telemt_desync_full_logged_total 16883
telemt_desync_suppressed_total 36397
telemt_desync_frames_bucket_total{bucket="1_2"} 11839
telemt_desync_frames_bucket_total{bucket="3_10"} 20744
telemt_desync_frames_bucket_total{bucket="gt_10"} 20697
telemt_pool_swap_total 194
telemt_pool_force_close_total 6489
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1044
telemt_me_draining_writers_reap_progress_total 59650
telemt_me_writer_removed_unexpected_total 1400
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5189
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55131
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6019
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53161
telemt_me_writer_teardown_success_total{mode="normal"} 60320
telemt_me_writer_teardown_noop_total 59703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 114319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 116697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 119413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 119984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 120014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 120015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 120019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 120021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 120023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 120023
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 316.922105
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 120023
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1044
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 1302
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 12885531
telemt_user_connections_current{user="hello"} 1096
telemt_user_octets_from_client{user="hello"} 189924611037 (176.88 GB)
telemt_user_octets_to_client{user="hello"} 3462195150823 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 505
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 179840.3 (49h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11756087
telemt_connections_bad_total 1206011
telemt_connections_current 735
telemt_connections_me_current 735
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343851
telemt_upstream_connect_attempt_total 94317
telemt_upstream_connect_success_total 93007
telemt_upstream_connect_fail_total 863
telemt_upstream_connect_attempts_per_request{bucket="1"} 93870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38554
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3794
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 863
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4320
telemt_me_reconnect_success_total 1810
telemt_me_reader_eof_total 1671
telemt_me_idle_close_by_peer_total 1671
telemt_me_route_drop_no_conn_total 4542622
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8742961
telemt_me_endpoint_quarantine_total 1158
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1365
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 38597
telemt_desync_full_logged_total 12983
telemt_desync_suppressed_total 25614
telemt_desync_frames_bucket_total{bucket="1_2"} 9534
telemt_desync_frames_bucket_total{bucket="3_10"} 14836
telemt_desync_frames_bucket_total{bucket="gt_10"} 14227
telemt_pool_swap_total 191
telemt_pool_force_close_total 5857
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 58013
telemt_me_writer_removed_unexpected_total 1706
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5311
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54259
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5345
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52156
telemt_me_writer_teardown_success_total{mode="normal"} 59570
telemt_me_writer_teardown_noop_total 58038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 115233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 116424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 117183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 117523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 117598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 117600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 117606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 117608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 117608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 117608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 117608
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.256171
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 117608
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 1542
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8680789
telemt_user_connections_current{user="hello"} 735
telemt_user_octets_from_client{user="hello"} 217254693076 (202.33 GB)
telemt_user_octets_to_client{user="hello"} 3933095178267 (3.58 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 310
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 179804.5 (49h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10961681
telemt_connections_bad_total 954811
telemt_connections_current 623
telemt_connections_me_current 623
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344954
telemt_upstream_connect_attempt_total 78397
telemt_upstream_connect_success_total 76872
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 77076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37030
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1956
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2339
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5594
telemt_me_reconnect_success_total 2292
telemt_me_reader_eof_total 2029
telemt_me_idle_close_by_peer_total 2028
telemt_me_route_drop_no_conn_total 5324730
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8296317
telemt_me_endpoint_quarantine_total 1239
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1322
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_desync_total 37873
telemt_desync_full_logged_total 12557
telemt_desync_suppressed_total 25316
telemt_desync_frames_bucket_total{bucket="1_2"} 9568
telemt_desync_frames_bucket_total{bucket="3_10"} 14486
telemt_desync_frames_bucket_total{bucket="gt_10"} 13819
telemt_pool_swap_total 187
telemt_pool_force_close_total 5770
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 730
telemt_me_draining_writers_reap_progress_total 58272
telemt_me_writer_removed_unexpected_total 2184
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6032
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54351
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5199
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52502
telemt_me_writer_teardown_success_total{mode="normal"} 60383
telemt_me_writer_teardown_noop_total 58343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 116571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 117644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 118618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 118626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 118639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 118672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 118675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 118726
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.605097
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 118726
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 730
telemt_me_refill_failed_total 175
telemt_me_writer_restored_same_endpoint_total 1984
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 8288307
telemt_user_connections_current{user="hello"} 623
telemt_user_octets_from_client{user="hello"} 192083846189 (178.89 GB)
telemt_user_octets_to_client{user="hello"} 3447301733525 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 50084.5 (13h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11087826
telemt_connections_bad_total 667023
telemt_connections_current 1092
telemt_connections_me_current 1092
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 253078
telemt_upstream_connect_attempt_total 51839
telemt_upstream_connect_success_total 49257
telemt_upstream_connect_fail_total 1741
telemt_upstream_connect_attempts_per_request{bucket="1"} 50998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16527
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5988
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1741
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7067
telemt_me_reconnect_success_total 1054
telemt_me_reader_eof_total 667
telemt_me_idle_close_by_peer_total 666
telemt_me_route_drop_no_conn_total 25265416
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9210628
telemt_me_endpoint_quarantine_total 346
telemt_me_single_endpoint_outage_enter_total 76
telemt_me_single_endpoint_outage_exit_total 76
telemt_me_single_endpoint_outage_reconnect_attempt_total 135
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 135
telemt_me_single_endpoint_shadow_rotate_total 396
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 15812
telemt_desync_full_logged_total 4206
telemt_desync_suppressed_total 11606
telemt_desync_frames_bucket_total{bucket="1_2"} 3025
telemt_desync_frames_bucket_total{bucket="3_10"} 6387
telemt_desync_frames_bucket_total{bucket="gt_10"} 6400
telemt_pool_swap_total 51
telemt_pool_force_close_total 1769
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 457
telemt_me_draining_writers_reap_progress_total 14856
telemt_me_writer_removed_unexpected_total 943
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2106
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13644
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1462
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13087
telemt_me_writer_teardown_success_total{mode="normal"} 15750
telemt_me_writer_teardown_noop_total 14875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30625
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.636729
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30625
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 457
telemt_me_refill_failed_total 327
telemt_me_writer_restored_same_endpoint_total 694
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 9235310
telemt_user_connections_current{user="hello"} 1092
telemt_user_octets_from_client{user="hello"} 85911065536 (80.01 GB)
telemt_user_octets_to_client{user="hello"} 571771665462 (532.50 GB)
telemt_user_msgs_from_client{user="hello"} 65206
telemt_user_msgs_to_client{user="hello"} 53386
telemt_user_unique_ips_current{user="hello"} 444
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 179811.1 (49h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10891496
telemt_connections_bad_total 927732
telemt_connections_current 918
telemt_connections_me_current 918
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 239485
telemt_upstream_connect_attempt_total 107192
telemt_upstream_connect_success_total 106076
telemt_upstream_connect_fail_total 946
telemt_upstream_connect_attempts_per_request{bucket="1"} 107022
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40495
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1353
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 946
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72718
telemt_me_reconnect_success_total 2969
telemt_me_reader_eof_total 2665
telemt_me_idle_close_by_peer_total 2663
telemt_me_route_drop_no_conn_total 5244294
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8600943
telemt_me_endpoint_quarantine_total 1181
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1349
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_desync_total 45884
telemt_desync_full_logged_total 15694
telemt_desync_suppressed_total 30190
telemt_desync_frames_bucket_total{bucket="1_2"} 9304
telemt_desync_frames_bucket_total{bucket="3_10"} 17563
telemt_desync_frames_bucket_total{bucket="gt_10"} 19017
telemt_pool_swap_total 183
telemt_pool_force_close_total 5460
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 653
telemt_me_draining_writers_reap_progress_total 62271
telemt_me_writer_removed_unexpected_total 2697
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6545
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58455
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4711
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56811
telemt_me_writer_teardown_success_total{mode="normal"} 65000
telemt_me_writer_teardown_noop_total 62272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 125138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 126536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 126955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 127228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 127262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 127265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 127265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 127268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 127272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 127272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 127272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 127272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 127272
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.182928
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 127272
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 653
telemt_me_refill_failed_total 4295
telemt_me_writer_restored_same_endpoint_total 2507
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 8604020
telemt_user_connections_current{user="hello"} 918
telemt_user_octets_from_client{user="hello"} 193870433217 (180.56 GB)
telemt_user_octets_to_client{user="hello"} 3285082664796 (2.99 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 400
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 116647.3 (32h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11552848
telemt_connections_bad_total 460929
telemt_connections_current 679
telemt_connections_me_current 679
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4736211
telemt_upstream_connect_attempt_total 55256
telemt_upstream_connect_success_total 54849
telemt_upstream_connect_fail_total 396
telemt_upstream_connect_attempts_per_request{bucket="1"} 55245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24904
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 396
telemt_me_reconnect_attempts_total 48691
telemt_me_reconnect_success_total 1729
telemt_me_reader_eof_total 1393
telemt_me_idle_close_by_peer_total 1392
telemt_me_route_drop_no_conn_total 4074005
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5558328
telemt_me_endpoint_quarantine_total 756
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 887
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31262
telemt_desync_full_logged_total 10647
telemt_desync_suppressed_total 20615
telemt_desync_frames_bucket_total{bucket="1_2"} 6201
telemt_desync_frames_bucket_total{bucket="3_10"} 12338
telemt_desync_frames_bucket_total{bucket="gt_10"} 12723
telemt_pool_swap_total 123
telemt_pool_force_close_total 3707
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 368
telemt_me_draining_writers_reap_progress_total 41275
telemt_me_writer_removed_unexpected_total 1447
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3534
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39228
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3266
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37568
telemt_me_writer_teardown_success_total{mode="normal"} 42762
telemt_me_writer_teardown_noop_total 41282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84044
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.634621
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84044
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 368
telemt_me_refill_failed_total 2729
telemt_me_writer_restored_same_endpoint_total 1534
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5550941
telemt_user_connections_current{user="hello"} 679
telemt_user_octets_from_client{user="hello"} 118516775996 (110.38 GB)
telemt_user_octets_to_client{user="hello"} 2140196354062 (1.95 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 97618.2 (27h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1461988
telemt_connections_bad_total 36395
telemt_connections_current 620
telemt_connections_me_current 620
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 29077
telemt_upstream_connect_attempt_total 45678
telemt_upstream_connect_success_total 45535
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 45650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24247
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 767
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2091
telemt_me_reconnect_success_total 859
telemt_me_reader_eof_total 837
telemt_me_idle_close_by_peer_total 837
telemt_me_route_drop_no_conn_total 504716
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1297369
telemt_me_endpoint_quarantine_total 791
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 804
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
telemt_me_writers_active_current 45
telemt_desync_total 8178
telemt_desync_full_logged_total 2473
telemt_desync_suppressed_total 5705
telemt_desync_frames_bucket_total{bucket="1_2"} 2038
telemt_desync_frames_bucket_total{bucket="3_10"} 3162
telemt_desync_frames_bucket_total{bucket="gt_10"} 2978
telemt_pool_swap_total 105
telemt_pool_force_close_total 2736
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 151
telemt_me_draining_writers_reap_progress_total 38279
telemt_me_writer_removed_unexpected_total 810
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3006
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36117
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2648
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35543
telemt_me_writer_teardown_success_total{mode="normal"} 39123
telemt_me_writer_teardown_noop_total 38283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77406
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.979042
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77406
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 151
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 729
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 1293273
telemt_user_connections_current{user="hello"} 620
telemt_user_octets_from_client{user="hello"} 25345070437 (23.60 GB)
telemt_user_octets_to_client{user="hello"} 552042770395 (514.13 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 179815.6 (49h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13214116
telemt_connections_bad_total 1567128
telemt_connections_current 1031
telemt_connections_me_current 1031
telemt_handshake_timeouts_total 379664
telemt_upstream_connect_attempt_total 68869
telemt_upstream_connect_success_total 68531
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 68733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34463
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2692
telemt_me_reconnect_success_total 1397
telemt_me_reader_eof_total 1367
telemt_me_idle_close_by_peer_total 1367
telemt_me_route_drop_no_conn_total 4471558
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9988879
telemt_me_endpoint_quarantine_total 1230
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1349
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 41750
telemt_desync_full_logged_total 13625
telemt_desync_suppressed_total 28125
telemt_desync_frames_bucket_total{bucket="1_2"} 10034
telemt_desync_frames_bucket_total{bucket="3_10"} 15365
telemt_desync_frames_bucket_total{bucket="gt_10"} 16351
telemt_pool_swap_total 199
telemt_pool_force_close_total 5422
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 662
telemt_me_draining_writers_reap_progress_total 62134
telemt_me_writer_removed_unexpected_total 1315
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5006
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58485
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5248
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56712
telemt_me_writer_teardown_success_total{mode="normal"} 63491
telemt_me_writer_teardown_noop_total 62136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 123060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 124735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 125118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 125494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 125614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 125627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 125627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 125627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 125627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 125627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 125627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 125627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 125627
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.591977
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 125627
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 662
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 1223
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 9955665
telemt_user_connections_current{user="hello"} 1031
telemt_user_octets_from_client{user="hello"} 194159598016 (180.83 GB)
telemt_user_octets_to_client{user="hello"} 4413454964544 (4.01 TB)
telemt_user_unique_ips_current{user="hello"} 368
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 179812.3 (49h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11508437
telemt_connections_bad_total 1313867
telemt_connections_current 585
telemt_connections_me_current 585
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 305413
telemt_upstream_connect_attempt_total 95401
telemt_upstream_connect_success_total 94552
telemt_upstream_connect_fail_total 642
telemt_upstream_connect_attempts_per_request{bucket="1"} 95194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40029
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 642
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10100
telemt_me_reconnect_success_total 2452
telemt_me_reader_eof_total 2287
telemt_me_idle_close_by_peer_total 2286
telemt_me_seq_mismatch_total 86
telemt_me_route_drop_no_conn_total 5631597
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8889348
telemt_me_endpoint_quarantine_total 1396
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 1352
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 41357
telemt_desync_full_logged_total 13275
telemt_desync_suppressed_total 28082
telemt_desync_frames_bucket_total{bucket="1_2"} 10617
telemt_desync_frames_bucket_total{bucket="3_10"} 15218
telemt_desync_frames_bucket_total{bucket="gt_10"} 15522
telemt_pool_swap_total 189
telemt_pool_force_close_total 5213
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 651
telemt_me_draining_writers_reap_progress_total 61938
telemt_me_writer_removed_unexpected_total 2322
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6346
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57994
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4742
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56725
telemt_me_writer_teardown_success_total{mode="normal"} 64340
telemt_me_writer_teardown_noop_total 61943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 123611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 125378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 125914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 126233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 126283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 126283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 126283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 126283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 126283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 126283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 126283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 126283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 126283
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.322241
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 126283
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 651
telemt_me_refill_failed_total 395
telemt_me_writer_restored_same_endpoint_total 1988
telemt_me_writer_restored_fallback_total 118
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 8894757
telemt_user_connections_current{user="hello"} 585
telemt_user_octets_from_client{user="hello"} 156835755769 (146.06 GB)
telemt_user_octets_to_client{user="hello"} 3462644762651 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 295
telemt_user_unique_ips_recent_window{user="hello"} 77
```