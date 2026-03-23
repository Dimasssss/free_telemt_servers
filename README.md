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

# Server Metrics 2026-03-23 02:06:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 104431.4 (29h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3594110
telemt_connections_bad_total 331572
telemt_connections_current 971
telemt_connections_me_current 971
telemt_handshake_timeouts_total 113329
telemt_upstream_connect_attempt_total 38920
telemt_upstream_connect_success_total 38919
telemt_upstream_connect_attempts_per_request{bucket="1"} 38919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25275
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1411
telemt_me_reconnect_success_total 614
telemt_me_reader_eof_total 631
telemt_me_idle_close_by_peer_total 631
telemt_me_route_drop_no_conn_total 2994629
telemt_me_route_drop_channel_closed_total 1234
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2953308
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 734
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 813
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_me_writers_warm_current 6
telemt_desync_total 12741
telemt_desync_full_logged_total 4014
telemt_desync_suppressed_total 8727
telemt_desync_frames_bucket_total{bucket="1_2"} 3397
telemt_desync_frames_bucket_total{bucket="3_10"} 4643
telemt_desync_frames_bucket_total{bucket="gt_10"} 4701
telemt_pool_swap_total 115
telemt_pool_force_close_total 3530
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 662
telemt_me_draining_writers_reap_progress_total 35627
telemt_me_writer_removed_unexpected_total 608
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2538
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33346
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3474
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32097
telemt_me_writer_teardown_success_total{mode="normal"} 35884
telemt_me_writer_teardown_noop_total 35638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71522
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 378.781583
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71522
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 662
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 550
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 2942305
telemt_user_connections_current{user="hello"} 971
telemt_user_octets_from_client{user="hello"} 42088082840 (39.20 GB)
telemt_user_octets_to_client{user="hello"} 805390159228 (750.08 GB)
telemt_user_unique_ips_current{user="hello"} 451
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 117797.1 (32h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4017592
telemt_connections_bad_total 371653
telemt_connections_current 392
telemt_connections_me_current 392
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 101013
telemt_upstream_connect_attempt_total 73350
telemt_upstream_connect_success_total 72455
telemt_upstream_connect_fail_total 788
telemt_upstream_connect_attempts_per_request{bucket="1"} 73243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31965
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 788
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10188
telemt_me_reconnect_success_total 3674
telemt_me_reader_eof_total 3660
telemt_me_idle_close_by_peer_total 3660
telemt_me_route_drop_no_conn_total 3643000
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3191339
telemt_me_endpoint_quarantine_total 948
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 46
telemt_me_single_endpoint_outage_exit_total 46
telemt_me_single_endpoint_outage_reconnect_attempt_total 47
telemt_me_single_endpoint_outage_reconnect_success_total 45
telemt_me_single_endpoint_quarantine_bypass_total 47
telemt_me_single_endpoint_shadow_rotate_total 921
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 13013
telemt_desync_full_logged_total 7305
telemt_desync_suppressed_total 5708
telemt_desync_frames_bucket_total{bucket="1_2"} 2951
telemt_desync_frames_bucket_total{bucket="3_10"} 5109
telemt_desync_frames_bucket_total{bucket="gt_10"} 4953
telemt_pool_swap_total 110
telemt_pool_force_close_total 3119
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 254
telemt_me_draining_writers_reap_progress_total 48645
telemt_me_writer_removed_unexpected_total 3589
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6342
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45926
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2661
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45526
telemt_me_writer_teardown_success_total{mode="normal"} 52268
telemt_me_writer_teardown_noop_total 48646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100914
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.640192
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100914
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 254
telemt_me_refill_failed_total 252
telemt_me_writer_restored_same_endpoint_total 3269
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 289
telemt_user_connections_total{user="hello"} 3204706
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 43232933394 (40.26 GB)
telemt_user_octets_to_client{user="hello"} 794959463182 (740.36 GB)
telemt_user_msgs_from_client{user="hello"} 49767
telemt_user_msgs_to_client{user="hello"} 185105
telemt_user_unique_ips_current{user="hello"} 258
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 192657.0 (53h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16380500
telemt_connections_bad_total 1659169
telemt_connections_current 1109
telemt_connections_me_current 1109
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 398150
telemt_upstream_connect_attempt_total 86538
telemt_upstream_connect_success_total 86432
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 86449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42405
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1722
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3028
telemt_me_reconnect_success_total 1604
telemt_me_reader_eof_total 1551
telemt_me_idle_close_by_peer_total 1549
telemt_me_route_drop_no_conn_total 14051552
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13006027
telemt_me_endpoint_quarantine_total 1285
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1450
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_me_writers_warm_current 22
telemt_desync_total 53950
telemt_desync_full_logged_total 17156
telemt_desync_suppressed_total 36794
telemt_desync_frames_bucket_total{bucket="1_2"} 12031
telemt_desync_frames_bucket_total{bucket="3_10"} 21069
telemt_desync_frames_bucket_total{bucket="gt_10"} 20850
telemt_pool_swap_total 208
telemt_pool_force_close_total 6787
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1065
telemt_me_draining_writers_reap_progress_total 65787
telemt_me_writer_removed_unexpected_total 1492
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5573
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60984
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6317
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59000
telemt_me_writer_teardown_success_total{mode="normal"} 66557
telemt_me_writer_teardown_noop_total 65840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 121229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 124901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 126677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 129069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 130736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 131787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 132358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 132388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 132389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 132393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 132395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 132397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 132397
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.831222
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 132397
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1065
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1387
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 13006033
telemt_user_connections_current{user="hello"} 1109
telemt_user_octets_from_client{user="hello"} 197317550253 (183.77 GB)
telemt_user_octets_to_client{user="hello"} 3500070124019 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 498
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 192658.3 (53h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11922223
telemt_connections_bad_total 1244245
telemt_connections_current 636
telemt_connections_me_current 636
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344804
telemt_upstream_connect_attempt_total 100901
telemt_upstream_connect_success_total 99571
telemt_upstream_connect_fail_total 877
telemt_upstream_connect_attempts_per_request{bucket="1"} 100448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53265
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42316
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3802
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 877
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4457
telemt_me_reconnect_success_total 1909
telemt_me_reader_eof_total 1773
telemt_me_idle_close_by_peer_total 1773
telemt_me_route_drop_no_conn_total 4561081
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8844371
telemt_me_endpoint_quarantine_total 1295
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1469
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_me_writers_warm_current 22
telemt_desync_total 38985
telemt_desync_full_logged_total 13131
telemt_desync_suppressed_total 25854
telemt_desync_frames_bucket_total{bucket="1_2"} 9660
telemt_desync_frames_bucket_total{bucket="3_10"} 14965
telemt_desync_frames_bucket_total{bucket="gt_10"} 14360
telemt_pool_swap_total 205
telemt_pool_force_close_total 6141
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 712
telemt_me_draining_writers_reap_progress_total 64006
telemt_me_writer_removed_unexpected_total 1802
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5670
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59995
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5629
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57865
telemt_me_writer_teardown_success_total{mode="normal"} 65665
telemt_me_writer_teardown_noop_total 64031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 122946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 126172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 127321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 128512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 129271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 129611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 129686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 129688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 129694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 129696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 129696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 129696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 129696
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.455651
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 129696
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 712
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1632
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 8782114
telemt_user_connections_current{user="hello"} 636
telemt_user_octets_from_client{user="hello"} 218031791476 (203.06 GB)
telemt_user_octets_to_client{user="hello"} 3971061407251 (3.61 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 192622.3 (53h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11086715
telemt_connections_bad_total 981736
telemt_connections_current 502
telemt_connections_me_current 502
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345699
telemt_upstream_connect_attempt_total 85177
telemt_upstream_connect_success_total 83618
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 83823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40745
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2034
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2363
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5773
telemt_me_reconnect_success_total 2394
telemt_me_reader_eof_total 2138
telemt_me_idle_close_by_peer_total 2137
telemt_me_route_drop_no_conn_total 5341456
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8377419
telemt_me_endpoint_quarantine_total 1351
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1428
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
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
telemt_desync_total 38232
telemt_desync_full_logged_total 12664
telemt_desync_suppressed_total 25568
telemt_desync_frames_bucket_total{bucket="1_2"} 9655
telemt_desync_frames_bucket_total{bucket="3_10"} 14634
telemt_desync_frames_bucket_total{bucket="gt_10"} 13943
telemt_pool_swap_total 201
telemt_pool_force_close_total 6040
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 745
telemt_me_draining_writers_reap_progress_total 64408
telemt_me_writer_removed_unexpected_total 2288
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6422
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60206
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5469
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58368
telemt_me_writer_teardown_success_total{mode="normal"} 66628
telemt_me_writer_teardown_noop_total 64479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 125266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 127989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 128952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 130025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 130626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 130840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 130968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 130999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 131007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 131020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 131053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 131056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 131107
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.839965
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 131107
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 745
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2083
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 8369364
telemt_user_connections_current{user="hello"} 502
telemt_user_octets_from_client{user="hello"} 192875260863 (179.63 GB)
telemt_user_octets_to_client{user="hello"} 3476734915005 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 62902.4 (17h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11302839
telemt_connections_bad_total 669613
telemt_connections_current 1021
telemt_connections_me_current 1021
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 280452
telemt_upstream_connect_attempt_total 59593
telemt_upstream_connect_success_total 56484
telemt_upstream_connect_fail_total 2038
telemt_upstream_connect_attempts_per_request{bucket="1"} 58522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19857
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6018
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2038
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7810
telemt_me_reconnect_success_total 1279
telemt_me_reader_eof_total 808
telemt_me_idle_close_by_peer_total 807
telemt_me_route_drop_no_conn_total 25297986
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9374056
telemt_me_endpoint_quarantine_total 467
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 505
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 16441
telemt_desync_full_logged_total 4499
telemt_desync_suppressed_total 11942
telemt_desync_frames_bucket_total{bucket="1_2"} 3124
telemt_desync_frames_bucket_total{bucket="3_10"} 6702
telemt_desync_frames_bucket_total{bucket="gt_10"} 6615
telemt_pool_swap_total 65
telemt_pool_force_close_total 2086
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 490
telemt_me_draining_writers_reap_progress_total 20051
telemt_me_writer_removed_unexpected_total 1164
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2649
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18510
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1779
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17965
telemt_me_writer_teardown_success_total{mode="normal"} 21159
telemt_me_writer_teardown_noop_total 20070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41229
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.945271
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41229
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 490
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 824
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 9399908
telemt_user_connections_current{user="hello"} 1021
telemt_user_octets_from_client{user="hello"} 87585507118 (81.57 GB)
telemt_user_octets_to_client{user="hello"} 621538605762 (578.85 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 435
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 192629.0 (53h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11041190
telemt_connections_bad_total 964559
telemt_connections_current 754
telemt_connections_me_current 754
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 242871
telemt_upstream_connect_attempt_total 114000
telemt_upstream_connect_success_total 112827
telemt_upstream_connect_fail_total 998
telemt_upstream_connect_attempts_per_request{bucket="1"} 113825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66963
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44261
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 998
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73051
telemt_me_reconnect_success_total 3120
telemt_me_reader_eof_total 2812
telemt_me_idle_close_by_peer_total 2810
telemt_me_route_drop_no_conn_total 5268205
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8702134
telemt_me_endpoint_quarantine_total 1302
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1456
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_me_writers_warm_current 2
telemt_desync_total 46354
telemt_desync_full_logged_total 15900
telemt_desync_suppressed_total 30454
telemt_desync_frames_bucket_total{bucket="1_2"} 9424
telemt_desync_frames_bucket_total{bucket="3_10"} 17740
telemt_desync_frames_bucket_total{bucket="gt_10"} 19190
telemt_pool_swap_total 197
telemt_pool_force_close_total 5754
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 666
telemt_me_draining_writers_reap_progress_total 68444
telemt_me_writer_removed_unexpected_total 2836
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6953
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64367
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5005
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62690
telemt_me_writer_teardown_success_total{mode="normal"} 71320
telemt_me_writer_teardown_noop_total 68445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 137613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 139029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 139448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 139721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 139755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 139758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 139758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 139761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 139765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 139765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 139765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 139765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 139765
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.287648
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 139765
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 666
telemt_me_refill_failed_total 4304
telemt_me_writer_restored_same_endpoint_total 2631
telemt_me_writer_restored_fallback_total 52
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 8705075
telemt_user_connections_current{user="hello"} 754
telemt_user_octets_from_client{user="hello"} 194947838777 (181.56 GB)
telemt_user_octets_to_client{user="hello"} 3327907570500 (3.03 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 356
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 129465.3 (35h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11741925
telemt_connections_bad_total 482861
telemt_connections_current 580
telemt_connections_me_current 580
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4766504
telemt_upstream_connect_attempt_total 62546
telemt_upstream_connect_success_total 62086
telemt_upstream_connect_fail_total 448
telemt_upstream_connect_attempts_per_request{bucket="1"} 62534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28818
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 448
telemt_me_reconnect_attempts_total 49092
telemt_me_reconnect_success_total 1859
telemt_me_reader_eof_total 1535
telemt_me_idle_close_by_peer_total 1534
telemt_me_route_drop_no_conn_total 4097868
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5643097
telemt_me_endpoint_quarantine_total 879
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 995
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 31771
telemt_desync_full_logged_total 10848
telemt_desync_suppressed_total 20923
telemt_desync_frames_bucket_total{bucket="1_2"} 6332
telemt_desync_frames_bucket_total{bucket="3_10"} 12536
telemt_desync_frames_bucket_total{bucket="gt_10"} 12903
telemt_pool_swap_total 137
telemt_pool_force_close_total 3967
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 379
telemt_me_draining_writers_reap_progress_total 47911
telemt_me_writer_removed_unexpected_total 1581
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3893
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45647
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3526
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43944
telemt_me_writer_teardown_success_total{mode="normal"} 49540
telemt_me_writer_teardown_noop_total 47918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97458
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.713461
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97458
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 379
telemt_me_refill_failed_total 2744
telemt_me_writer_restored_same_endpoint_total 1644
telemt_me_writer_restored_fallback_total 29
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5635233
telemt_user_connections_current{user="hello"} 580
telemt_user_octets_from_client{user="hello"} 120092951400 (111.85 GB)
telemt_user_octets_to_client{user="hello"} 2188011181126 (1.99 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 110436.0 (30h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1545416
telemt_connections_bad_total 36814
telemt_connections_current 435
telemt_connections_me_current 435
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 31592
telemt_upstream_connect_attempt_total 52230
telemt_upstream_connect_success_total 52069
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 52202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27027
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 796
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2292
telemt_me_reconnect_success_total 939
telemt_me_reader_eof_total 927
telemt_me_idle_close_by_peer_total 927
telemt_me_route_drop_no_conn_total 521943
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1373952
telemt_me_endpoint_quarantine_total 930
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 915
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
telemt_desync_total 9370
telemt_desync_full_logged_total 2699
telemt_desync_suppressed_total 6671
telemt_desync_frames_bucket_total{bucket="1_2"} 2754
telemt_desync_frames_bucket_total{bucket="3_10"} 3560
telemt_desync_frames_bucket_total{bucket="gt_10"} 3056
telemt_pool_swap_total 119
telemt_pool_force_close_total 3019
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 172
telemt_me_draining_writers_reap_progress_total 44292
telemt_me_writer_removed_unexpected_total 893
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3375
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41851
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2931
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41273
telemt_me_writer_teardown_success_total{mode="normal"} 45226
telemt_me_writer_teardown_noop_total 44296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89522
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.379413
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89522
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 172
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 800
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 1369749
telemt_user_connections_current{user="hello"} 435
telemt_user_octets_from_client{user="hello"} 26208315617 (24.41 GB)
telemt_user_octets_to_client{user="hello"} 582064128615 (542.09 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 192633.6 (53h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13364282
telemt_connections_bad_total 1614018
telemt_connections_current 659
telemt_connections_me_current 659
telemt_handshake_timeouts_total 390270
telemt_upstream_connect_attempt_total 76490
telemt_upstream_connect_success_total 76136
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 76354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38429
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3039
telemt_me_reconnect_success_total 1519
telemt_me_reader_eof_total 1503
telemt_me_idle_close_by_peer_total 1503
telemt_me_route_drop_no_conn_total 4486580
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10068191
telemt_me_endpoint_quarantine_total 1389
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1458
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_me_writers_warm_current 4
telemt_desync_total 42217
telemt_desync_full_logged_total 13784
telemt_desync_suppressed_total 28433
telemt_desync_frames_bucket_total{bucket="1_2"} 10250
telemt_desync_frames_bucket_total{bucket="3_10"} 15505
telemt_desync_frames_bucket_total{bucket="gt_10"} 16462
telemt_pool_swap_total 213
telemt_pool_force_close_total 5639
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 681
telemt_me_draining_writers_reap_progress_total 69185
telemt_me_writer_removed_unexpected_total 1440
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5401
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65277
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5465
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63546
telemt_me_writer_teardown_success_total{mode="normal"} 70678
telemt_me_writer_teardown_noop_total 69187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 137247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 138973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 139356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 139732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 139852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 139865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 139865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 139865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 139865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 139865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 139865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 139865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 139865
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.816843
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 139865
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 681
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1333
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 10034880
telemt_user_connections_current{user="hello"} 659
telemt_user_octets_from_client{user="hello"} 194936571308 (181.55 GB)
telemt_user_octets_to_client{user="hello"} 4446863572176 (4.04 TB)
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 192630.2 (53h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11675416
telemt_connections_bad_total 1364595
telemt_connections_current 560
telemt_connections_me_current 560
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 312240
telemt_upstream_connect_attempt_total 104036
telemt_upstream_connect_success_total 103137
telemt_upstream_connect_fail_total 691
telemt_upstream_connect_attempts_per_request{bucket="1"} 103828
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44027
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2068
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 691
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10645
telemt_me_reconnect_success_total 2627
telemt_me_reader_eof_total 2437
telemt_me_idle_close_by_peer_total 2436
telemt_me_seq_mismatch_total 101
telemt_me_route_drop_no_conn_total 5654120
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8983503
telemt_me_endpoint_quarantine_total 1572
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 53
telemt_me_single_endpoint_outage_exit_total 53
telemt_me_single_endpoint_outage_reconnect_attempt_total 53
telemt_me_single_endpoint_outage_reconnect_success_total 51
telemt_me_single_endpoint_quarantine_bypass_total 53
telemt_me_single_endpoint_shadow_rotate_total 1460
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_me_writers_warm_current 2
telemt_desync_total 41883
telemt_desync_full_logged_total 13490
telemt_desync_suppressed_total 28393
telemt_desync_frames_bucket_total{bucket="1_2"} 10829
telemt_desync_frames_bucket_total{bucket="3_10"} 15401
telemt_desync_frames_bucket_total{bucket="gt_10"} 15653
telemt_pool_swap_total 203
telemt_pool_force_close_total 5413
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 668
telemt_me_draining_writers_reap_progress_total 69257
telemt_me_writer_removed_unexpected_total 2479
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6788
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65036
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4942
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63844
telemt_me_writer_teardown_success_total{mode="normal"} 71824
telemt_me_writer_teardown_noop_total 69262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 138396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 140178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 140717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 141036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 141086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 141086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 141086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 141086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 141086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 141086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 141086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 141086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 141086
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.497616
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 141086
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 668
telemt_me_refill_failed_total 415
telemt_me_writer_restored_same_endpoint_total 2110
telemt_me_writer_restored_fallback_total 136
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 233
telemt_user_connections_total{user="hello"} 8988073
telemt_user_connections_current{user="hello"} 560
telemt_user_octets_from_client{user="hello"} 157544696936 (146.72 GB)
telemt_user_octets_to_client{user="hello"} 3500072692370 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 56
```